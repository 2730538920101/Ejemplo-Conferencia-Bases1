# Ejemplo-Conferencia-Bases1


## Recomendaciones

-   Utilizar una maquina virtual de cualquier distribución de linux para usar Docker, las mas utilizadas son las distribuciones basadas en Debian, CentOS y Ubuntu

-   Crear una carpeta "database" en la raíz del proyecto

-   Agregar un modelo físico (DDL) a la carpeta database

-   Como estaremos trabajando con Mysql debemos instalar la su imagen desde Dockerhub.com utilizando un Dockerfile o directamente desde el docker-compose.yaml, también es posible realizar los siguientes pasos desde cualqueira de los dos métodos:

    -   Definir correctamente los volúmenes y la persistencia

    -   Definir correctamente el punto de entrada

    -   Definir correctamente las variables de entorno

-   Crear una red para conectar los contenedores de backend y base de datos en el entorno de Docker.

-   Utilizar el docker-compose y su amplia gama de comandos para gestionar los contenedores. Existen comandos que nos pueden simplificar tareas si utilizamos los comandos de docker-compose en lugar de los comandos de docker cuando ya tenemos una aplicacion que cuenta con múltiples servicios.