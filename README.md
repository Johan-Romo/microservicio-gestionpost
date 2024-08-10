# Post Management Microservice
Este microservicio proporciona funcionalidades para la gestión de posts, incluyendo creación, actualización, eliminación y consulta de posts. Utiliza MongoDB como base de datos para el almacenamiento de la información y está diseñado para ser fácilmente integrable en una arquitectura de microservicios.
## Instalación 
1.Clonar el repositorio
2.Compila el proyecto usando Maven con el comando: mvn clean 
3.Configura MongoDB: Asegúrarse de tener una instancia de MongoDB corriendo. Se debe configurar la URL de conexión en src/main/resources/application.properties.
## Despliegue
Para ejecutar el microservicio localmente:
1. Construir la imagen Docker:
docker build -t microservicio-gestionpost.
2. Ejecutar el contenedor
   docker run -p 8080:8080 microservicio-gestionpost




