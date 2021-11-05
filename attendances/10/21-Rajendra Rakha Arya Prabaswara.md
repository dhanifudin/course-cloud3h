Nama : Rajendra Rakha Arya Prabaswara

NIM  : 1941720080

---

# What is Docker
Docker is a command-line program, a background daemon and a series of remotes
service by taking a logistical approach to solving common software problems
and simplify our experience of installing, running, publishing, and removing software.
Docker is not a programming language and not a framework for building software
Docker is a tool that helps us in solving common problems such as installing,
removing, upgrading, distributing, trustring, and managing software.


# Docker Background
Docker Packages the app with all the dependencies it needs
into a standard for deployment

Docker wraps everything into a complete filesystem that
contains everything the application needs and which runs the virtual machine itself.

# Docker History
Released in 2013 as open source, dotCloud is a platform provider
as as service which allows running applications without worrying about infrastructure issues.
To increase start up time, they use containers and docker

# Virtualization Vs Containerization
Allows creating a container in a Mac/Windows virtual environment on a laptop and executing commands or operating them.
Commands or operations performed on containers that run on local, will be the same as those that run on production.

# Docker Advantage
- Portability
- Quick deployment/teardown
- Managing infrastructure-like code
- Open source
- Consistency

# Terms on Docker
- Docker container: virtual machine or guest operating system, our application runs inside a docker container
- Docker client: a collection of command line commands to operate docker containers, for example creating containers,
  start/stop container, delete, and so on.
- Docker daemon: application running on the host machine. Docker server running in the background (as a daemon)
  and waiting for command from docker client
- Docker engine: a mix of applications running docker containers, docker clients, and docker daemons
- Docker image: template used to create containers. For example the image of ubuntu, CentOS, and so on.
- Docker registry: the place used to store docker images. Docker hub is a public registry
  which everyone can use. By default docker will search for images on docker hub
- Docker compose: a way that can be used to define
  and running more than one container.

# Basic docker commands
- docker run: a command to run containers
- docker build: used to create a docker image from a Dockerfile
- docker images: this command will display all existing images
- docker ps: will show a list of containers
- docker rm: command to delete one or more containers.
- docker rmi: command to delete an image or more than one image
- docker commit: used to make changes or file settings into a new image.
- docker push: command to upload image to server, docker hub.
- docker pull: command to fetch/download images from server, docker hub