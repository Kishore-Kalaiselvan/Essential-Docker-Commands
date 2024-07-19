## Docker Commands

`docker build` --> ***To Create a docker image using Dockerfile*** 

`docker build -t tagname <Dockerfile path>` --> ***To Create a docker image with own tag name***

`docker images` --> ***To View the Docker images that are present***

`docker image rm <imagename>` --> ***To Delete the Docker image***

`docker ps` --> ***To List the all running Docker Containers***

`docker stop $(docker ps -aq)` --> ***To Stop all the running Docker container***

`docker rmi -f $(docker images -aq)` --> ***To Delete All the Docker images (Before using this command check wheather the containers are Stopped)***

`docker login` --> ***To Login to dockerhub***

`docker tag <image_id> <username>/<image_name>:<tag>` --> ***To tag the image id with your username to make the image to be pushed to docker hub***

`docker push <username>/<image_name>:<tag>` --> ***To push the image to docker hub*** 
