Docker
Docker is a command-line program, a background daemon and a suite of remote services that takes a logistical approach to solving common software problems and simplifies our experience of installing, running, publishing, and removing software. Docker is not a programming language and is not a framework for building software. Docker is a tool that helps us in solving common problems such as installing, removing, upgrading, distributing, trustring, and managing software.

Docker Basic Commands
docker run: a command to run the container, when it is run for the first time it will search/download images.
docker build: used to create a docker image from a Dockerfile. This command will by default search in the current directory but can also use a specific PATH or URL.
docker images: this command will display all existing images, information such as tags and sizes will be displayed.
docker ps: will show a list of containers
docker rm: command to delete one or more containers.
docker rmi: command to delete an image or more than one image.
docker commit: used to make changes or file settings into a new image.
docker push: command to upload image to server, docker hub.
docker pull: command to fetch/download images from server, docker hub.
Dockerfile
A Dockerfile is a text document that contains all the commands a user can call on the command line to create an image. By using the Dockerfile we do not need to type commands one by one when creating an image.

Dockerfile command
FROM: an initialization command to retrieve an image from an existing repository.
MAINTENER: informs who performs maintenance on the created image.
LABEL: adds additional information to the image.
ADD/COPY: used to add files to a specific folder location
CMD: command to run a specific command
ENTRYPOINT: run certain script when docker boot
Containerization
Docker uses Linux Containers. Linux containers are usually called LXC which as of August 2018. Utilizes the linux kernel cgroups function from the linux kernel version 2.6.24. Linux container is an operating system virtualization that can be used to run multiple isolated Linux systems on a single host