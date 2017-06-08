Docker Run 

## Task

In this task we learn the first steps how to use docker

to use docker we will use the command docker.
The docker-command has a couple of options but we will start with the run option. After the run we will need to tell docker which image we need. For 
this exercise we use "docker/whalesay". Docker in the image name reflects the user who uploaded the image and whalesay the image. If we wouldnt give any parameters the container whould be started and exit directly. So add the the following after the image: cowsay hello world.

The full command is:
```
docker run docker/whalesay cowsay hello world
``` 

