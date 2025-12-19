# December Mini Project - CI/CD with GitHub Actions

## Overview
This project demonstrates a CI/CD pipeline for a Python application using GitHub Actions and Docker.
The pipeline builds a Docker image, pushes it to Docker Hub, and deploys the container to an AWS EC2 instance automatically.

GitHub Actions was used instead of Jenkins

---

## Technologies Used
- Python
- Docker
- GitHub Actions
- Docker Hub
- AWS EC2
- Git & GitHub

---

## CI/CD Pipeline Flow
1. Code is pushed to GitHub
2. GitHub Actions builds the Docker image
3. Image is pushed to Docker Hub
4. GitHub Actions connects to EC2 via SSH
5. EC2 pulls the Docker image
6. Container is started on EC2

---

## Docker Image Information
- **Image Name:** `naaasheley/december-mini-project`
- **Registry:** Docker Hub
- **Port Exposed:** `8000`

---



## Application Access
- **EC2 Public IP:** `98.81.229.27`
- **Application Port:** `8000`
- **URL:** http://98.81.229.27:8000/

---

## 📸 Screenshots (Deliverables)

### GitHub Actions Console Output
![GitHub Actions Console Output](images/Screenshot%202025-12-19%20at%2010.14.31%E2%80%AFPM.png)

### Docker Image name
![Docker Image ](images/Screenshot%202025-12-19%20at%2010.22.32%E2%80%AFPM.png)

### Application Running Live
![Application Running](images/Screenshot%202025-12-19%20at%2010.29.46%E2%80%AFPM.png)

### Contributors
All contributors are listed in the participants.txt file.