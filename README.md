# docker-networking
this is networking
sudo -i
docker network ls
docker network rm mahesh
docker network ls
docker network create  -d bridge 5pm batch
docker network ls
docker run  --name myc10 -d -p 83:80 nginx:latest
docker run  --name myc11- d -p 83:80 tomcat:latest
docker network connect 5pm batch myc10
docker network connect 5pm batch myc11
docker exec  -it myc10 /bin/bash
apt-get update
apt -get install iputils-ping


