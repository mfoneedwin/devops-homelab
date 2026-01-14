# DevOps Home Lab – Production CI/CD Platform

## 📌 Overview
Production-ready DevOps platform demonstrating CI/CD, Infrastructure as Code, containerization, Kubernetes, and monitoring.

## 🎯 Why This Project Exists

I built this DevOps home lab to demonstrate practical, production-aligned experience with:
- CI/CD automation (GitHub Actions)
- Containerization (Docker)
- Infrastructure as Code (Terraform)
- Kubernetes deployment patterns
- Monitoring and alerting (Prometheus/Grafana)
- Secure web delivery (Nginx + HTTPS)

The focus is on repeatable automation, debugging, and real operational workflows rather than one-off tutorials.


## 🧱 Architecture
<img width="1211" height="371" alt="Devop Architecture drawio" src="https://github.com/user-attachments/assets/486649a3-d833-4e33-8500-30e0afa1ab63" />


## 🛠 Tech Stack
- Node.js
- Docker & Docker Compose
- GitHub Actions
- Terraform
- Kubernetes
- Prometheus & Grafana
- Nginx + HTTPS

## 🚀 CI/CD Flow
1. Code pushed to GitHub
2. Tests & lint run
3. Docker image built & pushed
4. Infrastructure provisioned (Terraform)
5. App deployed automatically

## ⚙️ How to Run Locally
```bash
docker-compose up
