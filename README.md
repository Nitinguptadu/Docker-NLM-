# Docker computer vision codes 
# This is my first docker image this repo is for personal learning purpose 

# Testing Docker on linix and introduction to basic commands

docker images  -- for checking all images in local dir 

docker ps      -- it shows all running containers 

docker ps -a  -- it shows all containers 

# deleting dockers from local repo 

# first delete the docker container 

1)check all conatiners 4

docker ps -a

2) then delete the conatiners 

docker rm container-id

3)check docker images 

docker images 

4)Delete docker images

docker rmi docker-image-id

5) Delete all docker images in one command

docker rm $ (docker ps -a -q)

# Dockerizing your python application

step 1 create Dockerfile 

step 2 create requirements.txt

after creating all required file 

Dockerizing commads 

docker build -t 'nlm' .

a) upper command build docker image 

docker images

b) upper command check currently created image 

docker run -ti nlm

c) upper command run docker image file which we have created 

docker run -ti --name my_first__NML_docker_conatiner nml

d) upper command to rename your docker image


Pushing Docker local image to Docker Hub

step1  create docker repo on docker hub


step 2 docker tag 845f6f67c65a 06210621/exp_0621:latest ( exp_0621 is my repo name on docker hub at this place code will be pushed 

step 3 docker push 06210621/exp_0621:latest 





youtube video reffernce link https://www.youtube.com/watch?v=8uaDoMuDK6E&list=PLZsOBAyNTZwYHBIlu_PUO19M7aHMgwBJr












![Screenshot from 2020-02-05 12-53-15](https://user-images.githubusercontent.com/45600643/73819913-8d942c80-4816-11ea-9d95-c1c6fa44fc79.png)






