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
