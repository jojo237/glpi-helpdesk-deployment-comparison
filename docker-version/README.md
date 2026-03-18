# GLPI Deployment using Docker

## Overview
This version of the project demonstrates how to deploy GLPI using Docker containers.  
The goal is to provide a fast, reproducible, and clean deployment environment.

---

## Environment
- Ubuntu Server 24.04 (VM)
- Docker
- Docker Compose

---

## Architecture
The deployment is based on two main services:

- GLPI application container
- MySQL database container

These services are orchestrated using Docker Compose.

---

## Deployment Steps

### 1. Install Docker and Docker Compose

```bash
sudo apt update
sudo apt install docker.io docker-compose -y
```

---

### 2. Start the containers

```bash
docker-compose up -d
```

---

### 3. Verify running containers

```bash
docker ps
```

---

### 4. Access GLPI

Open your browser and go to:

```
http://<SERVER_IP>:8080
```

---

## Default Credentials

- Username: glpi  
- Password: glpi  

---

## Post-Installation

After logging in:

- Change the default password
- Remove the installation directory (if applicable)
- Configure users and entities
- Test ticket creation

---

## Advantages of Docker Deployment

- Fast setup
- Easy to reproduce
- Isolated environment
- Minimal configuration required

---

## Key Learnings

- Containerized applications simplify deployment
- Docker Compose helps manage multi-service applications
- Networking and volumes are key components in container setups

---

## Notes

This deployment was successfully completed and fully functional.  
It served as the baseline for comparison with a traditional deployment (aaPanel).
