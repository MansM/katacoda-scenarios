# Docker Run
To use docker we need to use the command "docker". The docker-command has a couple of options but we will start with the run option. The run option will launch a container. To tell docker which image it needs to start we add the imagename after run. For this exercise we use "docker/whalesay". Docker in the image name reflects the user who uploaded the image and whalesay the image. If we wouldnt give any parameters the container whould be started and exit directly. So add the the following after the image: cowsay hello world.

The full command is:
```
docker run user/imagename command to run in the container
``` 
 # Task
 Run a docker/whalesay container with the cowsay hello world command
