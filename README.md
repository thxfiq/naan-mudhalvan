# DevOps CI/CD Project with Jenkins, Docker, and Kubernetes

This project demonstrates a complete CI/CD pipeline using Jenkins, Docker, and Kubernetes.

## Stack
- Jenkins
- Docker
- Kubernetes
- Node.js
- GitHub

## Steps
1. Jenkins pulls code from GitHub.
2. Builds Docker image and pushes to Docker Hub.
3. Deploys to Kubernetes using `kubectl`.

## Kubernetes Access
Once deployed, access the app:
http://<your-node-ip>:30080
