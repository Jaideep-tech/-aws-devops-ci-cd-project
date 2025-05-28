# AWS DevOps CI/CD Project 🚀

A complete hands-on DevOps project demonstrating an end-to-end CI/CD pipeline using AWS and modern DevOps tools. The infrastructure is designed to simulate a scalable, production-like environment with automation and monitoring.

## 🛠️ Tech Stack

- **AWS** – EC2, S3, ECR, VPC, ALB, ASG, CloudWatch  
- **Terraform** – Infrastructure as Code (IaC)  
- **Docker** – Containerization  
- **Jenkins** – CI/CD automation  
- **Ansible** – Configuration management  
- **GitHub** – Source code management  
- **Monitoring** – CloudWatch (with optional Prometheus + Grafana simulated)

---

## 📁 Project Structure

aws-devops-ci-cd-project/
├── terraform/ # VPC, EC2, ALB, ASG definitions
├── ansible/ # Playbooks for server setup and app deploy
├── docker/ # Dockerfile and app containerization
├── jenkins/ # Jenkinsfile and job configuration
├── monitoring/ # CloudWatch setup, Prometheus config (optional)
└── README.md # Project overview

---

## 🎯 Project Goals

- Provision scalable AWS infrastructure using Terraform
- Automate configuration and deployment with Ansible
- Use Jenkins to implement CI/CD pipelines
- Containerize applications using Docker and host on EC2
- Monitor and alert using AWS CloudWatch (basic simulation)

---

## 🚀 CI/CD Pipeline Flow

1. Developer pushes code to **GitHub**
2. **Jenkins** triggers a job on commit
3. Build a Docker image and push to **ECR**
4. **Ansible** deploys the app to EC2 via **ALB**
5. **CloudWatch** monitors app and infra metrics with alerts

---

## 📷 Optional Enhancements

- Integrate **GitHub Actions** for alternative CI
- Use **Prometheus + Grafana** for advanced observability
- Host frontend with **S3 + CloudFront**
- Add **automated scaling policies** to ASG

---

## 📌 Notes

- This is a **learning and demonstration project** — not meant for production use as-is.
- All sensitive values are masked or simulated.

---

## 🤝 Contact

- 🔗 [LinkedIn](https://www.linkedin.com/in/jaideep-tonk-1267b91ba/)
- 💻 [GitHub](https://github.com/Jaideep-tech)
