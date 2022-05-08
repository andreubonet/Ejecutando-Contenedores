# Ejecutando-Contenedores

## EJEMPLO 1:
<p> Con el comando ">docker pull ubuntu:18.04" descargaremos una imagen de manera previa, para crear un contenedor de "ubuntu:18.04" y tener acceso a un shell en él. Si no hemos descargado la imagen de manera previa se decargará, para eso usaremos el comando "> docker run -it ubuntu:18.04 /bin/bash". Al crear el contenedor se nos da un acceso a un shell del mismo.</p>  

![Captura de pantalla 2022-05-08 a las 11 50 57](https://user-images.githubusercontent.com/91874398/167291483-37cf6a28-f97e-4c4a-b8be-5b8c19d031c8.png)

## EJEMPLO 2:
<p>Para crear un contendor de centOs:18.04 y listar el contenido de la carpeta/ ejecutaremos el comando "> docker run ubuntu:18.04 ls /" Al crear el contenedor se ejecuta la orden ls / y posteriormente el contenedor pasa a estar parado. Y ya no podremos acceder a él.</p>

![Captura de pantalla 2022-05-08 a las 12 01 14](https://user-images.githubusercontent.com/91874398/167291588-b74fcb98-9e23-4a2b-b099-07a8c94c1bc2.png)

## EJEMPLO 4:
<p>Para crear un contenedor de  debian 9 y mostrar el contenido de una carpeta establecida con el parámetro -w usaremos el comando "> docker run -it -w /etc debian:9 ls". Al crear el contenedor se ejecuta la orden ls desde el directorio /etc, posteriormente el contenedor pasa a estar parado. Y ya no podremos acceder a él. Conforme vayamos creando contenedores hay dos órdenes que nos van a interesar para hacer un seguimiento de qué tenemos en nuestro sistema: "docker ps" para mostrar los contenedores en ejeccución (Estado UP) y "docker ps -a" para mostrar todos los contenedores creados ya estén en ejecución (Estado Up) o parados (Estado Exited).</p>

![Captura de pantalla 2022-05-08 a las 11 57 03](https://user-images.githubusercontent.com/91874398/167291676-3765a7be-ac63-4005-88d2-01a9c6f52f5e.png)
