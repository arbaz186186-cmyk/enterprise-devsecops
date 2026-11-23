# Enterprise DevSecOps Platform

A company-level DevSecOps project demonstrating a secure and automated software delivery workflow.

## Project Overview

This project aims to build and deploy a professional company website using DevOps and DevSecOps tools.

## Technologies Used

- HTML
- CSS
- Git & GitHub
- Docker
- Jenkins
- SonarQube
- Trivy
- AWS
- Terraform
- Kubernetes
- Prometheus
- Grafana

## Current Progress

- [x] Company website created
- [x] Dockerfile created
- [x] Docker image built
- [x] Website running in Docker
- [x] GitHub repository created
- [ ] Jenkins CI/CD pipeline
- [ ] Security scanning
- [ ] AWS infrastructure
- [ ] Kubernetes deployment
- [ ] Monitoring setup

## Run Locally

```bash
docker build -t nexatech-website:v1 ./app

docker run -d --name nexatech-container -p 8090:80 nexatech-website:v1
