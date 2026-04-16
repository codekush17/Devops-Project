# DevOps Project

## Overview
This project demonstrates an end-to-end DevOps pipeline.

## Tech Stack
- Python (Flask)
- Docker
- Kubernetes
- GitHub Actions

## Features
- Containerized application using Docker
- CI pipeline using GitHub Actions
- Kubernetes Deployment and Service setup

## How to Run

### Docker
docker build -t devops-app ./app
docker run -p 5000:5000 devops-app

### Kubernetes
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## Access Application
http://localhost:30007
