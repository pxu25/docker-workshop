# Docker Workshop

This repository contains the content and directions to Insight Data Science's Docker workshop.
The goal of this workshop is to give participants an introduction to the basics behind Docker.
In this workshop, we will start with basics and end with the deployment of a system consiting of a
Jupyter notebook server and a PostgreSQL database.

## What is Docker?

[Docker](www.docker.com) is a popular containerization platform. Containerization is a lightweight alternative to virtualization that has gained widespread popularity due to its flexibility and ease of use. Docker in particular has emerged as the most popular framework for containerization. In combination with orchestration tools such as [Kubernetes](www.kubernetes.io), it is very easy to build dynamic microservice architectures.

## Prerequisites

Before starting the workshop, please [install Docker](www.docker.com/get-started). Note that as Docker is based on Linux features such as cgroups, the installation and usage of Docker on Windows can be cumbersome.

## Overview

The content of this workshop is divided into four chapters:

- [Chapter 1](./chapter1/README.md): Starting with the very basics of how to use Docker by building a container that runs Linux.
- [Chapter 2](./chapter2/README.md): Learning more about Docker by building a container that hosts a Jupyter notebook service.
- [Chapter 3](./chapter3/README.md): Learning how to use Docker to setup a database.
- [Chapter 4](./chapter4/README.md): Learning how to use docker-compose to orchestrate the deployment of multiple containers. In particular, we will deploy the two containers from Chapter 2 and 3 and connect them so that our Jupyter notebooks can access the database.
