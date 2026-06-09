# 🚀 Full-Stack 3-Tier Web Application on AWS

## 📌 Project Overview

Designed and deployed a production-style 3-tier web application using React.js, Node.js/Express.js, and MySQL, hosted on AWS cloud infrastructure. The project demonstrates modern DevOps practices including Infrastructure Design, CI/CD Automation, High Availability, Auto Scaling, Load Balancing, Monitoring, and Secure Network Architecture.

---

## 🏗️ Architecture

The application follows a 3-tier architecture:

### 1. Presentation Layer
- React.js frontend
- Serves user interface and client-side interactions
- Hosted on EC2 instances behind an Application Load Balancer

### 2. Application Layer
- Node.js & Express.js backend
- Handles business logic and API requests
- Deployed on private EC2 instances

### 3. Data Layer
- MySQL database
- Stores application data securely
- Isolated within private subnet architecture

---

## ☁️ AWS Infrastructure

### Network Architecture
- Designed a custom VPC across **2 Availability Zones**
- Created **6 Subnets**
  - Public Subnets
  - Private Application Subnets
  - Private Database Subnets
- Configured:
  - Internet Gateway
  - NAT Gateway
  - Route Tables
  - Security Groups
  - Network Isolation

### Compute Resources
- Bastion Host for secure administration
- Frontend EC2 Instances
- Backend EC2 Instances
- Auto Scaling Group for application servers

### Load Balancing
- Configured Application Load Balancer (ALB)
- Distributed incoming traffic across multiple instances
- Improved application availability and fault tolerance

---

## ⚙️ CI/CD Implementation

Implemented a fully automated CI/CD pipeline using AWS services:

### Pipeline Workflow
1. Source code pushed to GitHub
2. AWS CodePipeline triggers deployment
3. Application build and deployment process executes automatically
4. Updated application deployed to EC2 instances

### Benefits
- Faster deployments
- Reduced manual intervention
- Consistent release process
- Improved development workflow

---

## 📊 Monitoring & Logging

Implemented monitoring and observability using Amazon CloudWatch:

- Application performance monitoring
- Resource utilization tracking
- Log collection and analysis
- Infrastructure health monitoring
- Operational visibility and troubleshooting

---

## 🔐 Security Features

- Private subnet deployment for backend services
- Bastion host for secure SSH access
- Security Groups with least-privilege access
- Network segmentation using VPC architecture
- Controlled inbound and outbound traffic rules

---

## 🛠️ Technology Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL

### AWS Services
- VPC
- EC2
- Auto Scaling
- Application Load Balancer
- CodePipeline
- CloudWatch
- IAM
- Route Tables
- Internet Gateway
- NAT Gateway

### DevOps Tools
- Git
- GitHub
- CI/CD
- Linux

---

## 🎯 Key Achievements

✅ Built and deployed a complete 3-tier web application architecture

✅ Automated application deployment using AWS CodePipeline

✅ Designed a highly available VPC architecture across multiple Availability Zones

✅ Implemented Auto Scaling and Load Balancing for scalability

✅ Configured secure network infrastructure using public and private subnets

✅ Established centralized monitoring and logging with CloudWatch

✅ Applied real-world DevOps practices including automation, security, and infrastructure design

---

## 🚀 Future Enhancements

- Docker Containerization
- Kubernetes (EKS) Deployment
- Terraform Infrastructure as Code
- AWS RDS Integration
- AWS ECS Deployment
- Prometheus & Grafana Monitoring
- Blue-Green Deployment Strategy

---

## 👨‍💻 Author

**Sujith Kumar R**

Aspiring DevOps Engineer | Cloud Engineer | MERN Stack Developer

- GitHub: https://github.com/sujithkumarr99
- LinkedIn: Add Your LinkedIn Profile
