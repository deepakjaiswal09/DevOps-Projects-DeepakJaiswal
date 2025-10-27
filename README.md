# 🌩️ DevOps Internship Projects – Deepak Jaiswal

This repository contains my two major **DevOps projects** completed during my remote internship.  
Both projects demonstrate core principles of **automation, cloud deployment, and Infrastructure as Code (IaC)** using modern DevOps tools and cloud services.

---

## 📁 Repository Structure

```bash
DevOps-Projects-DeepakJaiswal/
│
├── Project-1-MultiCloud-Terraform/        # Multi-Cloud Infrastructure Automation (Terraform, AWS & GCP)
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   ├── providers.tf
│   └── README.md
│
├── Project-2-Jenkins-CICD-Docker-AWS/     # Automated CI/CD Pipeline (Jenkins, Docker & AWS)
│   ├── Dockerfile
│   ├── Jenkinsfile
│   ├── app/
│   └── README.md
│
└── Project-Report.pdf                     # Final formatted report for submission
```

# 🚀 Project 1 – Multi-Cloud Infrastructure Automation with Terraform, AWS & GCP

## 🧩 Overview

This project demonstrates multi-cloud infrastructure automation using Terraform to provision identical NGINX servers on AWS EC2 and GCP Compute Engine simultaneously.
It includes modular design, remote backend (S3), and cross-cloud provisioning in a single IaC workflow.

## 🧰 Tools & Services

Terraform · AWS EC2 · GCP Compute Engine · AWS S3 · VS Code · PowerShell

## 🌟 Key Highlights

-Modularized Terraform configuration for reusability.
-Remote backend with S3 for secured state management.
-Automated provisioning across AWS and GCP.
-Verified via public NGINX web server deployments.

## 🧠 Learnings

-Multi-provider Terraform integration.
-Secure backend management and credential handling.
-Cross-cloud deployment automation from a single codebase.

📄 Detailed steps, screenshots, and architecture diagram are available inside
Project-1-MultiCloud-Terraform/README.md

# 🧩 Project 2 – Automated CI/CD Pipeline with Jenkins, Docker & AWS

## 🔧 Overview

This project implements a production-grade CI/CD pipeline that takes source code from GitHub → Jenkins → Docker Hub → AWS EC2, automatically builds and deploys containers, and sends real-time build notifications via AWS SNS.

## 🛠 Tools & Services

Jenkins · Docker · AWS EC2 · Docker Hub · AWS SNS · GitHub · Node.js

## 🚀 Key Pipeline Stages

-Checkout: Pull latest code from GitHub.
-Build & Test: Docker image build and testing.
-Push: Upload new image to Docker Hub.
-Deploy: SSH to EC2 and run new container.
-Notify: Send build result via AWS SNS email.

## 🌟 Highlights

-Fully automated pipeline with no manual intervention.
-Secure credential management using Jenkins secrets.
-SNS notifications for real-time deployment feedback.
-Reusable CI/CD structure for future projects.

📄 Detailed explanation, screenshots, and configuration steps in
Project-2-Jenkins-CICD-Docker-AWS/README.md

## 📘 Final Report

For submission and evaluation, refer to the detailed report:
📄

## 🧩 Key Learnings from Internship

-Infrastructure as Code (IaC) with Terraform
-Continuous Integration & Deployment (CI/CD) pipelines
-Cloud provisioning across AWS and GCP
-Docker containerization and image management
-Cloud-based automation using Jenkins and AWS services
-Security best practices for credential and backend management

## 👨‍💻 Author

Deepak Jaiswal
Remote DevOps Intern | Cloud & Automation Enthusiast
deepakjaiswal9238@gmail.com

## 🌐 LinkedIn : https://www.linkedin.com/in/deepakjaiswal09/
