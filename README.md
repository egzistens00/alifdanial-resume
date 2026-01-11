# Alif Danial HTML Resume (Docker + AWS EKS)

[Live Resume](http://aae0b043aea004341bf1c33dbc775200-1758721560.ap-southeast-1.elb.amazonaws.com/) 🌐  

This repository contains a **Dockerized resume** deployed to **AWS EKS (Kubernetes)** and automatically updated via **GitHub Actions CI/CD**.

---

## Project Overview

This project demonstrates:

- Containerization of a **static HTML resume** using **Docker**
- Hosting on **AWS Elastic Kubernetes Service (EKS)**
- **Continuous Integration and Deployment (CI/CD)** with GitHub Actions
- Automated updates: any push to `main` triggers rebuild → ECR push → Kubernetes deployment update  

---

## Live Demo

View the resume online:  

[http://aae0b043aea004341bf1c33dbc775200-1758721560.ap-southeast-1.elb.amazonaws.com/](http://aae0b043aea004341bf1c33dbc775200-1758721560.ap-southeast-1.elb.amazonaws.com/)

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML       | Resume content |
| Docker     | Containerization |
| AWS ECR    | Container image registry |
| AWS EKS    | Kubernetes cluster hosting |
| GitHub Actions | CI/CD automation |
| AWS IAM   | Secure access for deployments |

---

## Local Testing

1. Build Docker image locally:
docker build -t resume-html .

2.Run locally:
docker run -p 8080:80 resume-html

3.Open in browser:
http://localhost:8080

---

## Author 
Alif Danial
