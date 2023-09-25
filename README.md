# Docker build [create image]
docker build . -t imagename

## see images
docker images

## run docker container
docker run imagename
### Or
docker run -d --name container_name imagename

## docker container kill and start and remove
docker kill container_id/container_name <br/>
docker stop container_id/container_name <br/>
docker start container_id/container_name <br/>
docker rm container_id/container_name

## see running conatiners
docker ps

## create container and port maping with our local machine to container
 docker run -d -p --name containername localMachinePort:containerExposedPort imagename

# Docker Volume 
