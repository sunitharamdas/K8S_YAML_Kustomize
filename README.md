## Kustomize: Simplified Configuration Management for Kubernetes
Read the full guide on **Kustomize**: [K8s YAML with Kustomize](https://medium.com/@suni.ramdas/k8s-yaml-with-kustomize-034f8f6574bf)

**Kustomize** is a powerful configuration management tool for Kubernetes. It allows you to customize Kubernetes manifests without altering the original YAML files. With Kustomize, you can manage Kubernetes deployments across multiple environments (e.g., dev, staging, and prod) using reusable and maintainable base configurations and overlays.

### Pre-requisites

To deploy an **EKS cluster** and a **3-tier application**, follow these resources:

- [GitHub Repository: 3-Tier Terraform EKS with Monitoring](https://github.com/sunitharamdas/3-Tier-Terraform-EKS-with-monitoring)
- [Medium Article: 3-Tier App with IaC, EKS Autoscaling, and Monitoring (Prometheus & Grafana)](https://medium.com/@suni.ramdas/3-tier-app-with-iac-eks-autoscaling-and-monitoring-prometheus-grafana-5f5b16fb7647)

Once the cluster and application are deployed, you can apply **Kustomize** on top of this setup for further customization.