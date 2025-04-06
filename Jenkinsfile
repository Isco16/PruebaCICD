pipeline {
  agent any
    environment {
        NODE_VERSION = '18' // Cambia si usas otra versión de Node.js
    }
  stages {
    stage('Checkout') {
      steps {
        echo '📥 Clonando el repositorio...'
        checkout scm
      }
    }
    stage('Instalar dependencias') {
      steps {
        bat 'npm install'
      }
    }

    stage('Test y cobertura') {
      steps {
        bat 'npm test -- --coverage'
      }
    }

    stage('Docker Build & Run') {
      steps {
        bat 'docker build -t js-app .'
        bat 'docker run -d -p 8083:3000 js-app'
        bat 'npm start &'
      }
    }
  }
}
