# Full-Stack CI/CD with React, Flask, Jenkins, Docker, and Kubernetes

## Overview
Production-ready CI/CD pipeline for a React.js frontend and Flask backend using Jenkins, Docker, and Kubernetes.

## Architecture Diagram

<img width="1536" height="1024" alt="architecture.png" src="https://github.com/user-attachments/assets/3f1333b6-d288-4e1b-88ea-9d4be583ceb9" />

![Architecture Diagram](docs/architecture.png) <!-- Placeholder: Replace with your diagram -->

## Setup Instructions

1. Clone the repository
2. Set up Docker and Kubernetes (minikube, kind, or cloud provider)
3. Configure Jenkins and webhooks
4. Update DockerHub credentials in Jenkins
5. Run `docker-compose up` for local development
6. Use `kubectl apply -f k8s/` for deployment

## Folder Structure
- `frontend/` - React app
- `backend/` - Flask app
- `jenkins/` - Jenkinsfile
- `k8s/` - Kubernetes manifests

## CI/CD Pipeline
- On code commit: Jenkins runs tests, lints, builds, pushes Docker images, and deploys to Kubernetes

## Replace placeholders and update as needed.
