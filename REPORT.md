## Reporte e instrucciones

- Npm install -y

![alt text](assets/images/image.png)

- Verificar correcto funcionamiento de app con "Postman" o "Thunder Client".

![alt text](assets/images/image-26.png)
![alt text](assets/images/image-27.png)
![alt text](assets/images/image-28.png)

- Git init

![alt text](assets/images/image-1.png)
 
- Touch .gitignore

![alt text](assets/images/image-2.png)

![alt text](assets/images/image-3.png)
 
- Touch README.md

![alt text](assets/images/image-4.png)

- Git status
 
 ![alt text](assets/images/image-5.png)

- Git add .

![alt text](assets/images/image-6.png)
 
- Git commit -m “Commit inicial del proyecto.”

![alt text](assets/images/image-7.png)
 
- Creacion repositorio remoto del proyecto

![alt text](assets/images/image-8.png)
 
- Comandos para sincronizar proyecto al repo remoto:
    - git branch -M main
    - git remote add origin https://github.com/Isco16/PruebaCICD.git
    - git push -u origin main
 
 ![alt text](assets/images/image-9.png)
![alt text](assets/images/image-10.png)
 
- Touch Dockerfile con su respectivo código.
 
 ![alt text](assets/images/image-11.png)
 ![alt text](assets/images/image-12.png)

- Actualización del repo remoto para subir el archivo Dockerfile.
 
![alt text](assets/images/image-13.png)

- Touch Jenkinsfile y su respectivo código.
 
 ![alt text](assets/images/image-14.png)
 ![alt text](assets/images/image-15.png)

- Subir nuevo archivo Jenkinsfile al repo remoto.
 
 ![alt text](assets/images/image-16.png)
 ![alt text](assets/images/image-17.png)

- Creación de pipeline de integración continua para el proyecto en Jenkins.
 
 ![alt text](assets/images/image-18.png)
 ![alt text](assets/images/image-19.png)
 ![alt text](assets/images/image-20.png)
 ![alt text](assets/images/image-21.png)

- Buildear el pipeline con las pruebas automatizadas y app dockerizada.

 ![alt text](assets/images/image-22.png)
 ![alt text](assets/images/image-23.png)
 ![alt text](assets/images/image-24.png)
 ![alt text](assets/images/image-25.png)

 # Resultados del pipeline

 - [Link reporte pdf](assets/reports/Reporte_4.pdf)
 - [Link reporte txt](assets/reports/#4.txt)