# CloudCart Platform

CloudCart is a cloud-native microservices platform deployed on AWS EKS using Terraform and managed via GitOps workflows.

The system simulates a minimal e-commerce backend to demonstrate Kubernetes infrastructure design, CI/CD automation, observability, and reliability engineering practices.

---

## Architecture Overview

- 3 Go-based microservices:
  - auth-service
  - payment-service
  - api-gateway
- PostgreSQL (persistent storage)
- Redis (caching layer)
- AWS EKS (Kubernetes control plane)
- Terraform (infrastructure provisioning)
- GitHub Actions (CI)
- ArgoCD (CD)
- Prometheus & Grafana (metrics and dashboards)
- ELK Stack (centralized logging)
- Horizontal Pod Autoscaling
- k6 load testing

---