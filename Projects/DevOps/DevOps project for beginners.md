# DevOps Project for Beginners 🚀

---

## Overview

This project covers deploying a 3-tier application to AWS EC2 using Docker, Nginx, and AWS ECR.

---

## 🟢 Basic Steps

1. **Create EC2 instance**
2. **Find 3-tier application** (Frontend, Backend, Database)
3. **Containerize application** with Docker
4. **Build Docker image** and push to AWS ECR
5. **SSH into EC2** and get AWS ECR credentials
6. **Pull Docker image** and start container
7. **Install Nginx** web server
8. **Configure Nginx** to point to local container
9. **Access application** on EC2 public IP

---

## 🔴 Advanced Steps

1. **Create GitHub Actions pipeline** for automated deployment
2. **Create EC2 IAM profile** for accessing AWS ECR
3. **Configure Route53 domain** and point to EC2 public IP

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|--------|
| AWS EC2 | Compute |
| Docker | Containerization |
| AWS ECR | Container Registry |
| Nginx | Reverse Proxy |
| GitHub Actions | CI/CD |
| Route53 | DNS |