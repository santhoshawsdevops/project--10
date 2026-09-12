# Flask Application Deployment Using Docker on AWS EC2

## Project Overview

Deployed a simple Flask web application on an Ubuntu Amazon EC2 instance using Docker. The application was containerized using a Dockerfile and exposed through Docker port mapping.

## Technologies Used

* AWS EC2
* Ubuntu Linux
* Docker
* Python
* Flask
* Git
* GitHub

## Implementation

* Created a simple Flask web application.
* Created `requirements.txt` to manage Python dependencies.
* Created a Dockerfile to build the application image.
* Built a Docker image using Docker.
* Created and ran a Docker container on an Ubuntu EC2 instance.
* Configured Docker port mapping from EC2 port `3000` to container port `5000`.
* Tested the application using `curl`.
* Used Docker commands such as `docker ps`, `docker ps -a`, and `docker logs` for monitoring and troubleshooting.
* Managed the project using Git and GitHub.

## Application Flow

GitHub → EC2 → Docker Image → Docker Container → Flask Application

## Docker Port Mapping

```text
EC2 Port 3000
      ↓
Docker Container Port 5000
      ↓
Flask Application
```

## Key Learning

This project helped me understand the complete basic workflow of containerizing an application and deploying it on AWS EC2, including Docker image creation, container management, port mapping, Git version control, and basic troubleshooting.
