# Week 1 — App Containerization

Before understanding what is docker let's first understand what is a container

A container can be thought of as a box containing all the necessary items. Containers contain your application and the libraries and dependencies required for it to run.
Containerizing your application will allow you to run it in any environment.

So what is docker, it is a platform for building, running, and managing containers.

What is Dockerfile?
Dockerfile is a text document containing a list of instructions to build an image. ```docker build``` is the command that is used to build docker images from the given dockerfile.

What is Docker Image?
Docker Image can be compared to a template that is used to create Docker Containers. You can use ```docker run``` to run the image and create a container. They stored in the docker registry

What are Docker containers?
Docker Containers are running instances of Docker Images, which contain all the packages necessary for running an application.

-How to install Docker on your localmachine and get the same containers running outside of Gitpod / Codespaces
To run docker on your local machine go to https://www.docker.com/products/docker-desktop/ and install docker desktop.

![Screenshot (129)](https://user-images.githubusercontent.com/59307860/221364268-15082f63-a3a8-4297-a8fc-e00cc722851f.png)
So this is how the docker desktop looks like


Now to run containers on this docker dekstop, go to your command prompt/ terminal and type ```docker run -d -p 80:80 docker/getting-started```
![Screenshot (128)](https://user-images.githubusercontent.com/59307860/221364857-33faa0bb-4bf9-4958-9aea-8adc6b54e713.png)

Lets understand what the command means: ```docker run``` is used to create a conatiner from the image specified. 
-d menas in detach mode
-p stands for ports the first argument 80 speifies the port we want to run the container and the second argument is the port of the conatiner. 
docker/getting-started is the name of the docker image


![Screenshot (129)](https://user-images.githubusercontent.com/59307860/221364770-66c49819-e4c1-47f4-b495-91de76bde8b7.png)
So now we can see our conatiner running in localhost at port 80 
