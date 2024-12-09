Kustomize: Simplified Configuration Management for Kubernetes

Kustomize is a powerful configuration management tool for Kubernetes. It allows you to customize Kubernetes manifests without altering the original YAML files. With Kustomize, you can manage Kubernetes deployments across multiple environments (e.g., dev, staging, and prod) using reusable and maintainable base configurations and overlays.

Pre-requisites

To deploy an EKS cluster and a 3-tier application, follow these resources:
	•	GitHub Repository: 3-Tier Terraform EKS with Monitoring
	•	Medium Article: 3-Tier App with IaC, EKS Autoscaling, and Monitoring (Prometheus & Grafana)

Once the cluster and application are deployed, you can apply Kustomize on top of this setup for further customization.