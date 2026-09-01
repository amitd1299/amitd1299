<div align="center">

# ⚡ AMIT DORWEKAR

### `DEVOPS & CLOUD ENGINEER`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=21&duration=2800&pause=700&color=00F7FF&center=true&vCenter=true&width=850&lines=AWS+%7C+DEVOPS+%7C+CLOUD+ENGINEERING;CI%2FCD+%7C+CONTAINERS+%7C+KUBERNETES;AUTOMATION+%7C+INFRASTRUCTURE+AS+CODE;BUILDING+PRODUCTION-STYLE+CLOUD+PLATFORMS;AUTOMATE+%E2%86%92+DEPLOY+%E2%86%92+MONITOR+%E2%86%92+IMPROVE" />

<br>

<img src="https://komarev.com/ghpvc/?username=amitd1299&label=PROFILE+VIEWS&color=0e75b6&style=for-the-badge" />

<br><br>

<a href="https://github.com/amitd1299">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/amit-dorwekar">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<img src="https://img.shields.io/badge/AWS-Certified-orange?style=for-the-badge&logo=amazonaws&logoColor=white"/>

</div>

---

# 🧠 ABOUT ME

> **DevOps / Cloud Engineer who learns by building, breaking and fixing real infrastructure.**

I build **production-style DevOps environments** covering the complete application delivery lifecycle — from source control and CI/CD automation to containerization, artifact management, Kubernetes deployment, infrastructure automation and monitoring.

My focus is on:

```text
        CODE
          ↓
      AUTOMATION
          ↓
       BUILD
          ↓
        TEST
          ↓
     CODE QUALITY
          ↓
     CONTAINERIZE
          ↓
       PACKAGE
          ↓
       DEPLOY
          ↓
      MONITOR
          ↓
     TROUBLESHOOT
          ↓
      IMPROVE 🚀
```

I prefer **hands-on infrastructure and real troubleshooting** over tutorial-only environments.

---

# 🛠️ TECHNOLOGY STACK

## ☁️ CLOUD & INFRASTRUCTURE

<p align="left">

<img src="https://skillicons.dev/icons?i=aws" height="55"/>
<img src="https://skillicons.dev/icons?i=linux" height="55"/>

<br>

<img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_IAM-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_VPC-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_SSM-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>

</p>

---

## 🔄 DEVOPS & CI/CD

<p align="left">

<img src="https://skillicons.dev/icons?i=git,github,jenkins,docker,kubernetes,terraform,ansible" />

<br><br>

<img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
<img src="https://img.shields.io/badge/K3s-FFC61C?style=for-the-badge&logo=kubernetes&logoColor=black"/>
<img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikmesh&logoColor=white"/>
<img src="https://img.shields.io/badge/Nexus-1B1F23?style=for-the-badge&logo=sonatype&logoColor=white"/>
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>

</p>

---

## 📊 MONITORING & OBSERVABILITY

<p align="left">

<img src="https://skillicons.dev/icons?i=prometheus,grafana" />

<img src="https://img.shields.io/badge/Jenkins_Monitoring-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes_Monitoring-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux_Monitoring-000000?style=for-the-badge&logo=linux&logoColor=white"/>

</p>

---

## 💻 PROGRAMMING & DEVELOPMENT

<p align="left">

<img src="https://skillicons.dev/icons?i=java,spring,python,bash,maven" />

</p>

---

# 🔥 FEATURED PROJECTS

## 🚀 01 — 3-TIER JAVA DEVOPS PLATFORM

### `Java • Spring Boot • Maven • JUnit • Jenkins • SonarQube • Docker • Nexus • K3s • Traefik • AWS`

A complete **3-Tier Java application delivery platform** implemented on AWS EC2 with automated CI/CD.

### ⚙️ ARCHITECTURE

```text
                         ┌───────────────┐
                         │    GitHub     │
                         └───────┬───────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │        Jenkins         │
                    │      CI/CD Engine      │
                    └───────────┬────────────┘
                                │
             ┌──────────────────┼──────────────────┐
             │                  │                  │
             ▼                  ▼                  ▼
         ┌────────┐        ┌────────┐        ┌──────────┐
         │ Maven  │        │ JUnit  │        │SonarQube │
         └────┬───┘        └────────┘        └──────────┘
              │
              ▼
        ┌──────────────┐
        │    Docker    │
        │ Build Image  │
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │    Nexus     │
        │Docker Registry│
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ K3s / Kubernetes│
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │   Traefik    │
        │ Traffic Entry│
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Java Backend │
        │     🚀       │
        └──────────────┘
```

### 🔁 PIPELINE

```text
GitHub
  ↓
Jenkins Checkout
  ↓
Maven Build
  ↓
JUnit Tests
  ↓
SonarQube Analysis
  ↓
Docker Build
  ↓
Nexus Docker Push
  ↓
K3s Deployment
  ↓
Traefik
  ↓
Deployment Verification
  ↓
✅ APPLICATION RUNNING
```

### 🧩 IMPLEMENTED

* Java-based 3-tier application
* Jenkins CI/CD pipeline
* Maven build automation
* JUnit testing
* SonarQube code-quality analysis
* Docker containerization
* Private Nexus Docker registry
* Kubernetes/K3s deployment
* Traefik traffic handling
* AWS EC2 Ubuntu infrastructure
* Deployment verification
* Linux and AWS infrastructure troubleshooting

### 🧯 REAL TROUBLESHOOTING

```text
ErrImagePull
      ↓
Docker Image Investigation
      ↓
k3s / containerd Analysis
      ↓
Image Import / Availability
      ↓
Pod Recovery
      ↓
1/1 Running ✅
```

Also worked through:

`Jenkins` • `Docker` • `Nexus` • `k3s` • `containerd` • `Traefik` • `SSH` • `Security Groups` • `EC2 IP Changes` • `Disk / Partition Management`

### 🔗 PROJECT

**[View 3-Tier Java DevOps Project →](https://github.com/amitd1299/java-3tier-devops)**

---

# 🚀 02 — OPSpilot

### `AWS • Jenkins • Docker • Nexus • Kubernetes/K3s • Terraform • Python`

An end-to-end **DevOps Control Center** focused on AWS infrastructure, CI/CD automation, container deployment and monitoring.

```text
GitHub
   ↓
Jenkins
   ↓
Build + Test
   ↓
Docker
   ↓
Nexus
   ↓
Kubernetes / K3s
   ↓
Deployment
   ↓
Health Verification
   ↓
Monitoring
```

### Highlights

* AWS EC2 infrastructure
* Jenkins automation
* Docker image lifecycle
* Nexus repository integration
* Kubernetes/K3s deployment
* Terraform infrastructure
* Application health checks
* Infrastructure troubleshooting
* AWS recovery workflows

### 🔗 PROJECT

**[View OpsPilot →](https://github.com/amitd1299/opspilot)**

---

# 🏗️ 03 — TERRAFORM + JENKINS AWS INFRASTRUCTURE

### `Terraform • AWS VPC • EC2 • ALB • S3 • DynamoDB • Jenkins`

Infrastructure-as-Code platform provisioning:

```text
GitHub
   ↓
Jenkins
   ↓
Terraform
   ↓
AWS VPC
   ├── Public Subnet
   ├── Route Tables
   ├── Security Groups
   ├── EC2
   ├── Application Load Balancer
   ├── Target Group
   └── Remote State
        ├── S3
        └── DynamoDB Lock
```

### 🔗 PROJECT

**[View Terraform AWS Infrastructure →](https://github.com/amitd1299/terraform-jenkins-aws-infra)**

---

# 🔧 04 — ANSIBLE INFRASTRUCTURE AUTOMATION

### `Ansible • AWS EC2 • Docker • Nginx`

Automation covering:

* Multi-server configuration
* Role-based playbooks
* Docker installation
* Nginx configuration
* Idempotent automation
* Reusable Ansible roles

### 🔗 PROJECT

**[View Ansible Automation →](https://github.com/amitd1299/ansible-infrastructure-automation)**

---

# 🌐 DEVOPS DELIVERY MODEL

<div align="center">

```text
┌──────────────┐
│    SOURCE    │
│    GitHub    │
└──────┬───────┘
       ↓
┌──────────────┐
│   BUILD/CI   │
│   Jenkins    │
└──────┬───────┘
       ↓
┌──────────────┐
│    QUALITY   │
│  SonarQube   │
└──────┬───────┘
       ↓
┌──────────────┐
│   CONTAINER  │
│    Docker    │
└──────┬───────┘
       ↓
┌──────────────┐
│    ARTIFACT  │
│    Nexus     │
└──────┬───────┘
       ↓
┌──────────────┐
│   ORCHESTRATE│
│ Kubernetes   │
│     / K3s    │
└──────┬───────┘
       ↓
┌──────────────┐
│    TRAFFIC   │
│   Traefik    │
└──────┬───────┘
       ↓
┌──────────────┐
│   MONITOR    │
│ Prometheus   │
│   Grafana    │
└──────────────┘

              🚀
```

</div>

---

# 📈 GITHUB ANALYTICS

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=amitd1299&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amitd1299&layout=compact&theme=tokyonight&hide_border=true" width="40%"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=amitd1299&theme=tokyonight&hide_border=true"/>

</div>

---

# 🐍 CONTRIBUTION ACTIVITY

<div align="center">

<img src="https://raw.githubusercontent.com/amitd1299/amitd1299/output/github-contribution-grid-snake-dark.svg" width="90%"/>

</div>

---

# 🏆 CERTIFICATION

<div align="center">

<img src="https://img.shields.io/badge/AWS-Certified%20Solutions%20Architect%20%E2%80%93%20Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>

<br><br>

**AWS Certified Solutions Architect – Associate**

</div>

---

# 🧠 DEVOPS MINDSET

```text
                 ┌───────────────┐
                 │    BUILD      │
                 └───────┬───────┘
                         ↓
                 ┌───────────────┐
                 │   AUTOMATE    │
                 └───────┬───────┘
                         ↓
                 ┌───────────────┐
                 │    DEPLOY     │
                 └───────┬───────┘
                         ↓
                 ┌───────────────┐
                 │    MONITOR    │
                 └───────┬───────┘
                         ↓
                 ┌───────────────┐
                 │ TROUBLESHOOT  │
                 └───────┬───────┘
                         ↓
                 ┌───────────────┐
                 │    IMPROVE    │
                 └───────────────┘
```

> **"Don't just deploy applications. Build the systems that deliver them."**

---

# 📫 CONNECT

<div align="center">

<a href="https://github.com/amitd1299">
<img src="https://img.shields.io/badge/GitHub-Amit%20Dorwekar-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/amit-dorwekar">
<img src="https://img.shields.io/badge/LinkedIn-Amit%20Dorwekar-0A66C2?style=for-the-badge&logo=linkedin"/>
</a>

<br><br>

### `AWS • DEVOPS • CLOUD • CI/CD • AUTOMATION`

**Open to DevOps & Cloud Engineering opportunities.**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=150&section=footer&text=AUTOMATE%20%7C%20DEPLOY%20%7C%20MONITOR&fontSize=22&fontColor=ffffff&animation=twinkling"/>

</div>
