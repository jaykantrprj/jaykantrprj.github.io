---
title: Introduction to Docker for absolute beginners
author: jaykantrprj
date: 2023-04-09 11:33:00 +0800
categories: [docker, container, deployment]
tags: [docker, container, deployment, open-source]
math: true
mermaid: true
---


> Introduction to docker for Beginner

## Docker: Introduction

Docker is a open platform for containerization, It gives simplified apporach for building, shipping, and running applications. With the help of docker application along with its dependecies into container. This container can be deployed to any enviornment with Docker installed. Which makes the deployment process easier and ensures you application runs consistentaly across differnet enviornments. 

It was first introduced in 2013 by Solomon Hykes as an open-source project, and it has since gained a popular in the software development community. It has become a one of the important tool in modern software development and is being used by many companies to streamline their development processes.

## Understanding Docker

Before we start with Docker it is important to undersatand difference between Docker and Virtual Machine. Virtual machine runs a entair operating system including it's kernel, on top of host operating system. Containers, on other hand share the host machine's operating system kernel and run as isolated processes in user space on top of the host operating system. since containers are not virtual machines, and they do not require a hypervisor to run.  Containers are particularly well-suited for deploying and running distributed applications that need to be deployed across multiple hosts or environments.


![Image Source:https://www.researchgate.net/figure/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13_fig1_343764931 ](https://www.researchgate.net/publication/343764931/figure/fig1/AS:926595288145920@1597928940339/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13.ppm "Image Source:https://www.researchgate.net/figure/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13_fig1_343764931 ")
Docker has a client-server architecture, where the Docker client communicates with the Docker daemon, which runs on the host machine. The Docker daemon manages the containers, images, networks, and volumes.

### The key components of Docker are:

- Dockerfile: A text file that contains the instructions for building a Docker image
- Docker image: A read-only template that contains the application and its dependencies
- Docker container: An instance of a Docker image that runs as a process on the host machine
- Docker registry: A repository for Docker images, such as Docker Hub

## Installing Docker
To get started with Docker, you need to install it on your machine. Docker is available for Windows, Mac, and Linux. You can follow the offical installation page https://docs.docker.com/engine/install/.

Once you've installed Docker, you can verify that it's working by running the hello-world image. This image is a simple example that prints a message to the console.
