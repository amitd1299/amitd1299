Hi there, I'm Amit Dorwekar 👋
🚀 Junior DevOps / Cloud Engineer | AWS Certified

I'm passionate about DevOps, Cloud Infrastructure, CI/CD automation, containerization, and Kubernetes.
I enjoy learning by building hands-on projects, troubleshooting real infrastructure problems, and understanding how different DevOps tools work together.

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazoniam&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)

### 🔄 DevOps & CI/CD
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=black)
![Nexus](https://img.shields.io/badge/Nexus_Repository-1B1C30?style=for-the-badge&logo=sonatype&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### 📊 Monitoring & Security
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=for-the-badge&logo=snyk&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP_Dependency--Check-000000?style=for-the-badge&logo=owasp&logoColor=white)

### 💻 Programming & OS
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Shell Scripting](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

## 🔥 Featured Projects

### 1. 🚀 OpsPilot — End-to-End DevOps CI/CD Platform
**Technologies: AWS EC2, Jenkins, GitHub, Docker, Nexus Repository, Kubernetes/K3s, Terraform, Python**

* Built an end-to-end CI/CD pipeline integrating GitHub, Jenkins, Docker, Nexus, and Kubernetes/K3s for automated application deployment.
* Automated build, testing, Docker image creation, Nexus image push, Kubernetes deployment, rollout verification, and application health checks.
* Provisioned and managed AWS EC2 infrastructure and practiced infrastructure configuration using Terraform.
* Troubleshot real-world issues involving Jenkins workspace permissions, Git authentication, Docker/K3s image handling, Nexus connectivity, Kubernetes image pulls, K3s/containerd, NodePort networking, and EC2 recovery.
* Deployed a Python Flask application on Kubernetes and verified successful application health through a live endpoint.

🔗 [View OpsPilot](https://github.com/amitd1299/opspilot)

---

### 2. 🔐 3-Tier Java CI/CD Pipeline — Jenkins, SonarQube & Nexus
**Java · Jenkins · SonarQube · Nexus · Docker · AWS EC2 · EKS**

A hands-on 3-tier DevOps project where Jenkins, SonarQube, and Nexus are set up on separate EC2 instances to build a complete CI/CD pipeline for a Java-based Maven application, including code quality analysis, dependency checks, artifact management, and Kubernetes (EKS) deployment.

**🔄 CI/CD Flow**
```
GitHub
   ↓
Jenkins (Build & Pipeline Orchestration)
   ↓
SonarQube (Code Quality & Static Analysis)
   ↓
OWASP Dependency-Check (Security Scan)
   ↓
Maven Build & Test
   ↓
Nexus Repository (Artifact Storage)
   ↓
Docker Image Build
   ↓
Amazon EKS (Deployment)
```

**What I implemented**
* Provisioned 3 separate EC2 instances (Jenkins, SonarQube, Nexus) on AWS
* Installed Jenkins with required plugins (SonarQube Scanner, Nexus Artifact Uploader, Docker, Docker Pipeline, OWASP Dependency-Check, Eclipse Temurin, Pipeline Maven Integration)
* Configured global tools in Jenkins (JDK 17, Maven, Dependency-Check, Docker)
* Ran SonarQube and Nexus via Docker containers
* Integrated Jenkins with SonarQube using authentication tokens for automated code quality gates
* Integrated Jenkins with Nexus via Maven `settings.xml` and repository credentials for artifact publishing
* Configured `pom.xml` with Nexus repository (release/snapshot) distribution management
* Set up an EKS cluster for application deployment

**🔧 Troubleshooting Experience**
* Jenkins plugin and tool version compatibility
* Docker container access and permission issues
* SonarQube-Jenkins token authentication
* Nexus repository credential and URL mismatches
* Maven `settings.xml` server ID mapping
* Security group/port configuration across 3 instances (8080, 9000, 8081)

🔗 View Project *(add repo link here)*

---

### 3. 🏗️ DevOps Infrastructure & CI/CD Practice
**Terraform · AWS · Jenkins · Docker · Kubernetes · Ansible**

Hands-on practice projects focused on building and automating cloud infrastructure and CI/CD workflows.

**Key areas practiced**
* AWS VPC and networking
* EC2 infrastructure
* Security Groups
* Terraform infrastructure provisioning
* Jenkins CI/CD pipelines
* Docker containerization
* Kubernetes deployments
* Ansible automation
* Monitoring with Prometheus and Grafana

---

### 4. ☁️ Terraform AWS Infrastructure
**Terraform · AWS VPC · EC2 · S3 · DynamoDB**

Infrastructure-as-Code practice focused on provisioning AWS resources using Terraform.

**Key areas**
* VPC configuration
* Public/private networking
* EC2 provisioning
* Security Groups
* Terraform variables and outputs
* Reusable infrastructure structure
* Remote state concepts

🔗 [View Project](https://github.com/amitd1299/terraform-aws-practice)

---

### 5. 🔧 Ansible Infrastructure Automation
**Ansible · AWS EC2 · Docker · Nginx**

Hands-on configuration-management practice using Ansible.

**Key areas**
* Remote server configuration
* Role-based playbooks
* Docker installation automation
* Nginx configuration
* Idempotent automation
* Reusable Ansible roles

🔗 [View Project](https://github.com/amitd1299/ansible-infrastructure-automation)

---

### 6. 🚀 Multi-Environment CI/CD Pipeline
**Jenkins · Docker · AWS EC2 · GitHub**

Practice project focused on understanding CI/CD promotion across multiple environments.

**Pipeline concept**
```
GitHub
   ↓
Jenkins
   ↓
Docker Build
   ↓
Development
   ↓
Staging
   ↓
Production
```

**Key areas**
* Jenkins pipelines
* Docker builds
* GitHub webhooks
* Environment-based deployments
* Manual approval gates
* AWS EC2 deployments

🔗 [View Project](https://github.com/amitd1299/flask-docker-app)

## 🏆 Certification
**AWS Certified Solutions Architect – Associate**

## 📊 GitHub Stats

![Amit's GitHub stats](https://github-readme-stats.vercel.app/api?username=amitd1299&show_icons=true&theme=default)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=amitd1299&layout=compact)

## 📫 Connect With Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amit-dorwekar/)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/u/amitdorwekar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amitd1299)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dorwekar2000@gmail.com)
