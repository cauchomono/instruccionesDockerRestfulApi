
Pasos para ejecutar la restfulapi Locaciones:

1. Se debe descargar la imagen docker de postgres, el front y el back end, por medio una consola de comandos
(como windows powershell), usando siguientes comandos (linea por linea):

docker pull postgres:14.2-alpine

docker pull sebasforero/locacionesbackend:v1

docker pull sebasforero/locacionesfrontend:v1

2. Descargar el archivo docker-compose.yml del mismo repositorio donde se descargo estas instrucciones

3. Colocar el archivo docker-compose.yml en la misma ruta en la que se esta ejecutando la consola

4. En la consola de comandos, ejecutar la siguiente linea:
docker-compose up

5. Esperar a que se ejecuten las imagenes docker completamente

6. En el navegador web ingresar la url:
http://localhost:4200/ 
