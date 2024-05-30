# Docker-Two-Tier-App
## Introduction
This repository provides guidance on deploying a two-tier application using Docker. It consolidates basic Docker commands into a single file for easy reference.
## Docker Commands
### Docker Installation
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
### Checking Docker Version
Check Docker version:<br>
docker --version

## Docker Command Reference
### Monitoring and Information
**docker stats:** Displays live resource usage statistics for running Docker containers. <br>
**docker info:** Displays detailed information about the Docker installation, including container and image counts.<br>
### Image Management
**docker images:** Lists all images on the Docker host.<br>
**docker pull <image_name>:** Downloads an image from a Docker registry.<br>
**docker rmi <image_name>:** Removes one or more images from the Docker host.<br>
### Container Management
**docker ps:** Lists all running containers.<br>
**docker ps -a:** Lists all containers, including stopped ones.<br>
**docker run <image_name>:** Creates and starts a container from an image.<br>
**docker run -d <image_name>:** Runs a container in detached mode.<br>
**docker run --name <container_name> <image_name>:** Runs a container with a specific name.<br>
**docker start <container_id_or_name>:** Starts a stopped container.<br>
**docker stop <container_id_or_name>:** Stops a running container.<br>
**docker restart <container_id_or_name>:** Restarts a running or stopped container.<br>
**docker rm <container_id_or_name>:** Removes a container.<br>
### Logs and Execution
**docker logs <container_id_or_name>:** Fetches the logs of a container.<br>
**docker exec -it <container_id_or_name> /bin/bash:** Runs a command in a running container, typically used to start an interactive shell.<br>
**docker cp <host_path> <container_id_or_name>:<container_path>:** Copies files or directories from the host to a container.<br>
**docker cp <container_id_or_name>:<container_path> <host_path>:** Copies files or directories from a container to the host.<br>
### Network Management
**docker network ls:** Lists all Docker networks.<br>
**docker network create <network_name>:** Creates a new Docker network.<br>
**docker network inspect <network_name>:** Displays detailed information about a Docker network.<br>
**docker network connect <network_name> <container_id_or_name>:** Connects a container to a network.<br>
**docker network disconnect <network_name> <container_id_or_name>:** Disconnects a container from a network.<br>
### Volume Management
**docker volume ls:** Lists all Docker volumes.<br>
**docker volume create <volume_name>:** Creates a new Docker volume.<br>
**docker volume inspect <volume_name>:** Displays detailed information about a Docker volume.<br>
**docker volume rm <volume_name>:** Removes a Docker volume.<br>


