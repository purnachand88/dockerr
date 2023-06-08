docker architecture
-here we can build direct application
-docker itself can check and adjust its storage depends on file
-it is used in server side 
-


docker have 

-> Tomcat
->Linux
-> Virtual machine
->Windows
-> Laptop


4 main thuings 9in docker

IMAGES
-docker [image] (dockerpull image_name)
-docker [containers] (docker commit container_name/container_id new image_name)
-docker [host] (docker rmi image_nqme/image_id)
-docker [hub] (docker push image_name)
-To create a image from docker file (docker build -t mew_image_name)
-To search for a docker image (docker search image_name)
-To delee all images that are not attached to containers (docker system prune -a)

CONTAINERS
-docker container ls (to see ruu=nning containers)
-To see list of all running and astopped containers (docker psm -a)
-To start a container (docker start comntainer_name/containe_id)
-To stop a container (docker stop conatiner_mname/container_id)
-Restart running container (docker restart container_name/container_id)

