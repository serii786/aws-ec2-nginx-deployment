# 🚀 AWS EC2 + NGINX Deployment

My first hands-on Cloud Lab - Deployed a live web server on AWS.

## 🌐 Live Demo
*Status:* Welcome to nginx! page is LIVE ✅

## 🛠️ Tech Stack
- AWS EC2
- Amazon Linux 2023
- NGINX
- SSH
- Linux Terminal

## 📋 Steps I Followed

### 1. Launch EC2 Instance
- OS: Amazon Linux 2023
- Created Key Pair (.pem file)
- Allowed Port 22 (SSH) and Port 80 (HTTP) in Security Group

### 2. Connect via SSH
```bash
ssh -i dic.pem ec2-user@YOUR-EC2-PUBLIC-IP
