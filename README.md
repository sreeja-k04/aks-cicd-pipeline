# Kubernetes CI/CD Deployment using Azure DevOps

## Project Overview

This project demonstrates the implementation of an end-to-end CI/CD pipeline for deploying a containerized application to Azure Kubernetes Service (AKS) using Azure DevOps.

The application is containerized using Docker, pushed to DockerHub, and automatically deployed to AKS using Kubernetes manifests and Azure DevOps pipelines.

---

## Technologies Used

- Docker
- Kubernetes
- Azure Kubernetes Service (AKS)
- Azure DevOps
- DockerHub
- YAML Pipelines

---

## Features

- Dockerized application deployment
- Automated CI/CD pipeline
- Kubernetes Deployment and Service configuration
- DockerHub image integration
- AKS cluster deployment
- LoadBalancer service exposure
- Image pull secret configuration

---

## Project Structure

```text
.
├── azure-pipelines.yml
├── Dockerfile
├── index.html
├── k8s
│   ├── deployment.yaml
│   └── service.yaml
└── Project_Documentation.pdf
