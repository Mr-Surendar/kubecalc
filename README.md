██████╗ ███████╗██╗   ██╗███████╗███████╗ ██████╗ ██████╗ ███████╗
██╔══██╗██╔════╝██║   ██║██╔════╝██╔════╝██╔════╝██╔═══██╗██╔════╝
██║  ██║█████╗  ██║   ██║███████╗█████╗  ██║     ██║   ██║███████╗
██║  ██║██╔══╝  ╚██╗ ██╔╝╚════██║██╔══╝  ██║     ██║   ██║╚════██║
██████╔╝███████╗ ╚████╔╝ ███████║███████╗╚██████╗╚██████╔╝███████║
╚═════╝ ╚══════╝  ╚═══╝  ╚══════╝╚══════╝ ╚═════╝ ╚═════╝ ╚══════╝

# 🚀 DevSecOps Kubernetes Pipeline

> End-to-End DevSecOps CI Pipeline using Jenkins, Docker, Kubernetes, SonarQube, Helm, Prometheus and Grafana.

![Architecture](asset\1784183342009.png)

---

## 📌 Overview

This project demonstrates an end-to-end DevSecOps pipeline for deploying a containerized web application into Kubernetes using Jenkins.

The pipeline performs:

- Static Code Analysis using SonarQube
- Quality Gate Validation
- Docker Image Build
- Docker Image Push
- Kubernetes Deployment
- Cluster Monitoring using Prometheus & Grafana

---