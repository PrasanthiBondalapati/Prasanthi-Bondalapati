# Hi, I'm Prasanthi Bondalapati 👋

### Aspiring AWS Cloud & DevOps Engineer

I'm a 2025 B.Tech graduate in Artificial Intelligence and Data Science, preparing for entry-level opportunities in AWS Cloud, DevOps, and Cloud Support.

## 🛠️ Technical Skills

- **Cloud:** AWS EC2, S3, IAM, VPC, RDS, ALB, Auto Scaling, Route 53, CloudWatch
- **Operating System:** Linux
- **Scripting:** Bash / Shell Scripting
- **Version Control:** Git, GitHub
- **Infrastructure as Code:** Terraform
- **CI/CD and Build Tools:** GitHub Actions, Maven
- **Code Quality and Artifacts:** SonarQube, Nexus
- **Containers and Deployment:** Docker, Apache Tomcat

## 🚀 Projects

### 1. AWS Three-Tier Web Application
- Practiced designing a three-tier application architecture on AWS.
- Worked with VPC, public and private subnets, EC2, Application Load Balancer, Auto Scaling, and RDS.
- Explored monitoring with Amazon CloudWatch.

### 2. Java Application CI/CD Pipeline
- Practiced a CI/CD workflow using Git, GitHub, Maven, SonarQube, Nexus, and Tomcat.
- Explored build automation, code quality checks, artifact management, and application deployment.

## 📚 Currently Learning
- Docker and containerization
- AWS Cloud and DevOps hands-on projects
- CI/CD and infrastructure automation

## 🎯 Career Goal
Seeking an entry-level AWS Cloud Engineer, Junior DevOps Engineer, or Cloud Support role where I can apply my skills and continue learning.

## 📫 Connect With Me
- **GitHub:** [PrasanthiBondalapati](https://github.com/PrasanthiBondalapati)

## Architecture Overview

The project follows a three-tier architecture:

1. **Web tier:** Handles incoming web traffic through a load balancer.
2. **Application tier:** Hosts application workloads on EC2 instances.
3. **Database tier:** Stores application data using Amazon RDS for MySQL.

### Networking and Availability
- Amazon VPC with public and private subnets
- Internet Gateway for public internet connectivity
- NAT Gateway for outbound connectivity from private subnets
- Resources planned across two Availability Zones

### Security Considerations
- Use security groups to restrict traffic between tiers.
- Keep the database private and allow access only from the application tier.
- Never store AWS credentials or private keys in the repository.

### Project Status
This repository documents my AWS learning and hands-on practice. Implementation details reflect the steps documented in the accompanying project PDF.
