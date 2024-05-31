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

# Protocols and Ports

This part provides a list of common protocols and their associated ports used in DevOps engineering projects. Understanding these protocols and ports is crucial for setting up, securing, and managing a robust DevOps environment.

## Table of Contents

1. [HTTP/HTTPS](#httphttps)
2. [SSH](#ssh)
3. [SMTP](#smtp)
4. [IMAP/POP3](#imappop3)
5. [FTP/SFTP](#ftpsftp)
6. [NFS](#nfs)
7. [CIFS/SMB](#cifssmb)
8. [RDP](#rdp)
9. [VNC](#vnc)
10. [DNS](#dns)
11. [LDAP](#ldap)
12. [SNMP](#snmp)
13. [NTP](#ntp)
14. [Redis](#redis)
15. [Elasticsearch](#elasticsearch)
16. [Logstash](#logstash)
17. [Kibana](#kibana)
18. [RabbitMQ](#rabbitmq)
19. [Kafka](#kafka)
20. [Consul](#consul)
21. [Vault](#vault)
22. [Kubernetes API Server](#kubernetes-api-server)
23. [Docker Daemon](#docker-daemon)
24. [Prometheus](#prometheus)
25. [Grafana](#grafana)

## Protocols and Ports

### HTTP/HTTPS
- **Ports**: 80 (HTTP), 443 (HTTPS)
- **Usage**: Web traffic, API communication, webhooks.

### SSH
- **Port**: 22
- **Usage**: Secure remote login, command execution, file transfer.

### SMTP
- **Ports**: 25 (SMTP), 587 (SMTP with STARTTLS), 465 (SMTPS)
- **Usage**: Sending emails, notifications from CI/CD pipelines.

### IMAP/POP3
- **Ports**: 143 (IMAP), 993 (IMAPS), 110 (POP3), 995 (POP3S)
- **Usage**: Retrieving emails.

### FTP/SFTP
- **Ports**: 21 (FTP), 990 (FTPS), 22 (SFTP)
- **Usage**: File transfers between systems.

### NFS
- **Port**: 2049
- **Usage**: File sharing across networked systems.

### CIFS/SMB
- **Port**: 445
- **Usage**: Network file sharing, especially in Windows environments.

### RDP
- **Port**: 3389
- **Usage**: Remote desktop access to Windows machines.

### VNC
- **Ports**: 5900+
- **Usage**: Remote desktop access to Unix-like systems.

### DNS
- **Port**: 53
- **Usage**: Domain name resolution.

### LDAP
- **Ports**: 389 (LDAP), 636 (LDAPS)
- **Usage**: Directory services, authentication.

### SNMP
- **Ports**: 161 (SNMP), 162 (SNMPTRAP)
- **Usage**: Network management, monitoring.

### NTP
- **Port**: 123
- **Usage**: Time synchronization across systems.

### Redis
- **Port**: 6379
- **Usage**: In-memory data store, caching.

### Elasticsearch
- **Port**: 9200
- **Usage**: Search engine, logging, and analytics.

### Logstash
- **Port**: 5044
- **Usage**: Log collection and processing.

### Kibana
- **Port**: 5601
- **Usage**: Data visualization and exploration.

### RabbitMQ
- **Ports**: 5672 (AMQP), 15672 (Management Console)
- **Usage**: Message broker.

### Kafka
- **Port**: 9092
- **Usage**: Distributed streaming platform, message broker.

### Consul
- **Ports**: 8500 (HTTP API), 8600 (DNS)
- **Usage**: Service discovery, configuration.

### Vault
- **Port**: 8200
- **Usage**: Secrets management, data encryption.

### Kubernetes API Server
- **Port**: 6443
- **Usage**: Kubernetes cluster management.

### Docker Daemon
- **Ports**: 2375 (non-SSL), 2376 (SSL)
- **Usage**: Container management.

### Prometheus
- **Port**: 9090
- **Usage**: Monitoring and alerting.

### Grafana
- **Port**: 3000
- **Usage**: Data visualization, dashboards.

## Conclusion

Understanding and configuring these protocols and ports are essential for effective DevOps practices. Proper usage ensures secure and efficient communication, data transfer, and system management within a DevOps environment.

**docker volume inspect <volume_name>:** Displays detailed information about a Docker volume.<br>
**docker volume rm <volume_name>:** Removes a Docker volume.<br>


