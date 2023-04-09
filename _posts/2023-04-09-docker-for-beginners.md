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
Before we dive into Docker, it's important to understand the difference between virtual machines and containers. Virtual machines emulate a complete operating system, including its kernel, on top of a host operating system. Containers, on the other hand, share the host operating system's kernel and only package the application and its dependencies. This makes containers much lighter and more efficient than virtual machines.

Before we start with Docker it is important to undersatand difference between Docker and Virtual Machine. Virtual machine runs a entair operating system including it's kernel, on top of host operating system.

![Image Source:https://www.researchgate.net/figure/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13_fig1_343764931 ](https://www.researchgate.net/publication/343764931/figure/fig1/AS:926595288145920@1597928940339/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13.ppm "Image Source:https://www.researchgate.net/figure/Comparison-of-Docker-Container-and-Virtual-Machine-Architecture-13_fig1_343764931 ")