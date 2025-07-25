# E-Commerce Platform with Auto Scaling and Blue-Green Deployments
# E-Commerce Platform with Blue-Green Deployments

## Overview
This project sets up a production-ready E-Commerce platform using:

- Kubernetes on AWS EKS
- Blue-Green Deployments with Argo Rollouts
- GitOps via ArgoCD
- CI/CD using GitHub Actions
- Monitoring with Prometheus & Grafana

## Components

### Frontend
React-based frontend served via container on EKS

### Backend
Express/Django-based backend connected to PostgreSQL

### Infrastructure
Provisioned using Terraform:
- AWS VPC, EKS, RDS

### CI/CD
- GitHub Actions pipeline for container build and deployment

### Monitoring
- Prometheus for metrics
- Grafana for dashboards

## Deployment Flow
1. Code pushed to GitHub triggers CI/CD
2. Docker images built and pushed to registry
3. Manifests updated in Git repo
4. ArgoCD syncs changes to EKS
5. Argo Rollouts handles progressive delivery

---

To proceed, let m


Scalable e-commerce system with GitOps and advanced deployment strategies.

## 🛠️ Author

This project is maintained by **[Fardis](https://github.com/fardeskhan)** 💡.
Your feedback and contributions are welcome!

📧 **Connect with me:**
- **GitHub**: [@fardeskhan](https://github.com/fardeskhan)
- **LinkedIn**: [Fardis Khan](https://www.linkedin.com/in/fardiskhan/)

---

## ⭐ Support the Project

If you found this project helpful, please consider:
- **Starring** ⭐ the repository
- **Sharing** it with your network
- **Contributing** to its improvement

> [!Important]
> This documentation is continuously evolving. For the latest updates, please check the repository regularly.

### 📢 Stay Connected  

![Follow Me](https://i.postimg.cc/02cVx2Z2/readmeimg2.png)
