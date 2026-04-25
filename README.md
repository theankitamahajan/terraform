# ☁️ Cloud-Native Infrastructure with Terraform

## 🚀 Project Overview

This repository contains the **Infrastructure as Code (IaC)** used to provision and manage highly available cloud environments. This architecture was designed to support **Spring Boot microservices** and **AI-driven automation workflows**, similar to my work with the **Government of Ontario**.

## 🛠 Key Technical Tasks

- **Automated Provisioning:** Used Terraform to manage AWS ECS and Azure AKS containerized environments.
- **Network Security:** Configured VPCs, Security Groups, and IAM roles to ensure secure inter-service communication.
- **CI/CD Integration:** Integrated infrastructure deployments with **GitHub Actions** for seamless release cycles.

## 🏗 Architecture

- **Provider:** AWS / Azure
- **Services:** ECS, RDS, S3, CloudWatch
- **State Management:** Remote S3 backend with DynamoDB locking.

## 📖 How to Use

1. Initialize: `terraform init`
2. Plan: `terraform plan`
3. Deploy: `terraform apply`
