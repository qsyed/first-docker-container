# first-docker-container



# steps to remember:
> docker build --tage website:latest . 
### in the same directory where the docker file live use this command  to build the docker image
### the . represent the directory where the docker file is, in our case we are in the same dir.

> docker run --name website -p 8080:80 -d website:latest
### launching a docker container name webiste based of the image we have built.
