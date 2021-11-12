Docker takes away repetitive, mundane configuration tasks and is used throughout the development lifecycle for fast, easy and portable application development - desktop and cloud. Docker’s comprehensive end to end platform includes UIs, CLIs, APIs and security that are engineered to work together across the entire application delivery lifecycle.
In today's class, we learned how to build an image from a container.
1. Create a Base Container:
2. Inspect Images
3. Inspect Containers
4. Start the Container
5. Modify the Running Container
6. Create an Image From a Container
7. Tag the Image
8. Create Images With Tags
9. Delete the Original Container
10. Look at Running Containers
11. Consider Your Options
    There are a few optional things we can do using the commit command that will change information about our images.
    For example, we might want to record who the author of our image is or capture a commit message telling us about the state of the image. 
    These are all controlled through optional parameters to the commit command.
    Let’s go back to our original running container. We are going to use a slightly      different command here to make cleanup easier:
    thought -docker run --name nginx_base --rm -d -p 80:80 nginx:alpine
    This command will run the image nginx:alpine with the name nginx_base; the                 creation of the image will be included in the command execution.

    The –rm will cause the container to be deleted when it is shut down. The -d tells the       command line client to run in detached mode. This will allow us to run other commands       from the same terminal.
We went through changing things about the running container above
The docker commit subcommand is very useful for diagnostic activities and bootstrapping new images from existing containers.

As I showed above, there are many helpful options available, too. The Docker CLI has many other power commands. 
