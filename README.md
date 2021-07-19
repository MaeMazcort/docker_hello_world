# docker_hello_world
Hola mundo e introducción al dockerfile y las imágenes

### Hacer una imagen
* docker build -t <nombre> .

### Ver las imágenes que tenemos
* docker images

### Acceder a la imagen
* docker run -it <nombre> bash

### Correr el contenedor en detach mode
* docker run -d <nombre>

### Contenedores activos
* docker ps

### Todos los contenedores 
* docker ps -a

### Logs
* docker logs <id_contenedor>

### Parar el contenedor
* docker stop <nombre>

### Eliminar el contenedor
* docker rm <nombre>

### Eliminar la imagen
* docker rmi <nombre>
