# docker
para los comandos docker

#listar imagenes en docker:
docker images

#listar los contenedores ejecutandose
docker ps -a

#ejecutar imagen docker
docker run <nombre_imagen>

#eliminar imagen
docker rmi <imageID>

#lista historial de imagenes
docker history <ImageID>
  
#detener contenedor
docker stop <containerid>

#eliminar contenedor
docker rm <containerid>
