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

#listar ids de contenedores
docker ps -a -q

#eliminar contenedores
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)

#docker container prune /eliminar todos los contenedores
docker container prune
docker image prune

#docker ip
docker-machine ip
