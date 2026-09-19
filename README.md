# Docker Task

## Objective

Install Docker on an AWS EC2 instance and explore commonly used Docker commands.

## Technologies Used

- AWS EC2
- Docker
- Docker Compose

## Docker Commands Explored

### Docker Installation

Verified Docker and Docker Compose versions.

    docker --version
    docker compose version

### Docker Images

Listed available Docker images using:

    docker images

### Docker Containers

Checked running and all containers using:

    docker ps
    docker ps -a

### Docker Volumes

Listed existing volumes and created a Docker volume:

    docker volume ls
    docker volume create docker-task-2-volume

### Docker Networks

Listed Docker networks and created a custom bridge network:

    docker network ls
    docker network create docker-task-2-network

## Screenshots

The screenshots folder contains evidence of Docker installation verification, Docker images, Docker containers, Docker volumes, and Docker networks.

## Result

Docker was successfully installed on AWS EC2 and the required Docker images, containers, volumes, and networks commands were explored and verified.
