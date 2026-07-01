# DevOps CI/CD Project

## Project Overview

This project demonstrates an end-to-end DevOps pipeline for a Spring Boot application using Jenkins, Docker, Kubernetes, Prometheus, and Grafana.

## Architecture

GitHub → Jenkins → Docker → Kubernetes → Prometheus → Grafana

## Technologies Used

* Linux
* Git & GitHub
* Java 17
* Spring Boot
* Maven
* Jenkins
* Docker
* Kubernetes (Minikube)
* Prometheus
* Grafana

## Features

* Automated CI/CD pipeline using Jenkins
* Dockerized Spring Boot application
* Kubernetes deployment with scaling
* Rolling updates and rollback
* Monitoring using Prometheus and Grafana

## Project Screenshots

* Jenkins Pipeline Success
* Kubernetes Pods Running
* Application Running
* Grafana Dashboard

## Useful Commands

```bash
kubectl get pods
kubectl get svc
kubectl scale deployment devops-demo --replicas=4
kubectl rollout undo deployment/devops-demo
docker build -t devops-demo:v1 .
```

