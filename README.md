<div align="center">

# Dhiraj Dwivedi

### DevOps Engineer · Cloud Automation · CI/CD

**GCP · AWS · Kubernetes · Terraform · Docker · GitHub Actions · Python**

I build and automate reliable cloud infrastructure, deployment pipelines, and
containerized platforms with a focus on **automation, reliability, security, and cost optimization**.

[![GitHub](https://img.shields.io/badge/GitHub-DhirajCloud-181717?style=for-the-badge\&logo=github)](https://github.com/DhirajCloud)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dhiraj_Dwivedi-0A66C2?style=for-the-badge\&logo=linkedin)](https://www.linkedin.com/in/dhiraj-dwivedi/)
[![Email](https://img.shields.io/badge/Email-dheerajd172%40gmail.com-EA4335?style=for-the-badge\&logo=gmail)](mailto:dheerajd172@gmail.com)

</div>

---

## About

I'm a **DevOps Engineer / Cloud Engineer with 4 years of enterprise experience**
working across **Google Cloud Platform and AWS**.

My work focuses on turning manual infrastructure and deployment processes into
repeatable, automated workflows using **Infrastructure as Code, CI/CD,
containerization, Kubernetes, and scripting**.

I enjoy solving infrastructure problems, improving deployment reliability,
reducing operational toil, and building systems that are easier to operate
and scale.

### Engineering Focus

* ☁️ Cloud infrastructure and automation
* 🔄 CI/CD pipeline design and deployment automation
* 🏗️ Infrastructure as Code with Terraform
* 🐳 Docker containerization
* ☸️ Kubernetes / GKE workloads
* 🐍 Python & Bash automation
* 🐧 Linux infrastructure operations
* 🔐 IAM, security hardening and least-privilege practices
* 📊 Reliability, monitoring and incident response
* 💰 Cloud cost optimization

---

## Professional Impact

| Area            | Experience                                         |
| --------------- | -------------------------------------------------- |
| ☁️ Cloud        | GCP & AWS                                          |
| 🚀 Deployment   | Reduced release cycles from 2 hours to <20 minutes |
| 🛡️ Reliability | Supported systems operating at 99.99% uptime       |
| 💰 Optimization | Delivered infrastructure cost reductions           |
| ⚙️ Automation   | Python, Bash, Terraform & CI/CD                    |
| 🐳 Containers   | Docker & Kubernetes/GKE                            |
| 🔐 Security     | IAM, hardening & vulnerability remediation         |
| 🏢 Enterprise   | 4 years of cloud & infrastructure experience       |

---

## Technology Stack

### Cloud

<p>
<img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

**GCP:** Compute Engine · VPC · IAM · Cloud Load Balancing · Cloud Storage ·
Cloud Functions · GKE · BigQuery

**AWS:** EC2 · S3 · IAM · VPC · CloudWatch · ELB

### DevOps & Infrastructure

<p>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

### Automation & Development

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
</p>

### Data & Cloud Services

`BigQuery` · `Dataflow` · `Cloud Composer` · `SQL`

### Networking & Security

`VPC` · `Subnets` · `DNS` · `Load Balancing` · `Firewall Rules` · `IAM`
· `Least Privilege` · `Security Hardening`

---

## Featured Engineering Projects

### 🚀 Zero-Downtime Deployment System

A production-style deployment platform demonstrating automated application
delivery with containerization and Kubernetes.

**Focus areas**

* Docker containerization
* Kubernetes deployments
* CI/CD automation
* Rolling deployment strategy
* Application health checks
* Deployment validation
* Rollback-oriented deployment design

**Architecture**

```text
Developer
    │
    ▼
Git Repository
    │
    ▼
CI/CD Pipeline
    │
    ├── Test
    ├── Build
    └── Validate
    │
    ▼
Docker Image
    │
    ▼
Container Registry
    │
    ▼
Kubernetes
    │
    ├── Current Version
    └── New Version
            │
            ▼
      Rolling Deployment
            │
            ▼
      Health Verification
            │
            ▼
        Application
```

🔗 **Repository:**
https://github.com/DhirajCloud/zero-downtime-deployment

---

### ☁️ DevOpsForge Cloud Platform

An end-to-end cloud-native platform demonstrating infrastructure provisioning,
containerization, Kubernetes deployment, CI/CD and observability.

**Technology**

`AWS` · `Terraform` · `Docker` · `Kubernetes/EKS` · `GitHub Actions`
· `Prometheus` · `Grafana` · `FastAPI`

**Architecture**

```text
                    ┌─────────────────┐
                    │    Developer    │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │     GitHub      │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │ GitHub Actions  │
                    │ CI/CD Pipeline  │
                    └────────┬────────┘
                             │
                     ┌───────┴────────┐
                     ▼                ▼
                  Testing         Docker Build
                                      │
                                      ▼
                                   AWS ECR
                                      │
                                      ▼
                              ┌──────────────┐
                              │   AWS EKS    │
                              │              │
                              │  Pod  ─ Pod  │
                              │      │       │
                              │      ▼       │
                              │     HPA      │
                              └──────┬───────┘
                                     │
                                     ▼
                              Load Balancer
                                     │
                                     ▼
                                   Users

             Terraform → Infrastructure Provisioning

             Prometheus → Metrics
             Grafana    → Visualization
```

🔗 **Repository:**
https://github.com/DhirajCloud/devopsforge-cloud-platform

---

## DevOps Architecture

My preferred engineering workflow follows a simple principle:

```text
              ┌──────────────┐
              │     Code     │
              └──────┬───────┘
                     │
                     ▼
              ┌──────────────┐
              │     Git      │
              └──────┬───────┘
                     │
                     ▼
              ┌──────────────┐
              │     CI       │
              │ Test / Lint  │
              └──────┬───────┘
                     │
                     ▼
              ┌──────────────┐
              │ Docker Build │
              └──────┬───────┘
                     │
                     ▼
              ┌──────────────┐
              │   Registry   │
              └──────┬───────┘
                     │
                     ▼
              ┌──────────────┐
              │ Kubernetes   │
              │   / Cloud    │
              └──────┬───────┘
                     │
              ┌──────┴───────┐
              ▼              ▼
        ┌───────────┐  ┌────────────┐
        │ Monitoring│  │  Security  │
        └─────┬─────┘  └──────┬─────┘
              │               │
              └───────┬───────┘
                      ▼
               Continuous
                Improvement
```

---

## Infrastructure as Code

I use **Terraform** to make infrastructure repeatable, version-controlled,
and easier to maintain.

```text
Terraform
    │
    ├── Networking
    │     ├── VPC
    │     ├── Subnets
    │     └── Firewall Rules
    │
    ├── Compute
    │     ├── VM / EC2
    │     └── Kubernetes
    │
    ├── IAM
    │
    └── Application Infrastructure
```

The goal is simple:

> **Infrastructure should be reproducible instead of manually recreated.**

---

## Automation Mindset

I focus on identifying repetitive operational work and turning it into
repeatable automation.

```text
Manual Process
      │
      ▼
Identify Repetition
      │
      ▼
Automate
      │
      ├── Python
      ├── Bash
      ├── Terraform
      └── CI/CD
      │
      ▼
Measure Result
      │
      ▼
Improve Reliability
```

This approach has helped reduce deployment time, infrastructure setup effort,
manual troubleshooting and operational overhead in enterprise environments.

---

## Reliability & Operations

My experience includes:

* Production infrastructure troubleshooting
* Incident response and SLA management
* Linux and Windows cloud infrastructure
* OS patching and security hardening
* IAM and access management
* Network troubleshooting
* Load balancing
* Capacity planning
* Cloud cost optimization
* Automation of recurring operational tasks

At Cognizant, I worked on GCP infrastructure automation and global
load-balancing solutions, including systems supporting 99.99% uptime.

Previously, I supported 500+ infrastructure and deployment incidents across
GCP and AWS and developed Python/Bash automation that reduced MTTR by 25%.

---

## Certifications

* **Google Cloud Professional Cloud DevOps Engineer — 2026**
* **Google Cloud Professional Data Engineer — 2026**
* **Google Cloud Associate Cloud Engineer — 2024**

---

## Currently Deepening

I'm continuing to expand my cloud and DevOps engineering capabilities,
particularly around the Google Cloud data and automation ecosystem.

```text
BigQuery
   │
   ▼
Dataflow
   │
   ▼
Cloud Composer
   │
   ▼
Automated Data Pipelines
```

I'm also continuing to build hands-on projects around:

* Kubernetes
* CI/CD
* Terraform
* Cloud automation
* Observability
* Production deployment patterns
* Infrastructure security

---

## Engineering Principles

```text
01  Automate repetitive work
02  Treat infrastructure as code
03  Make deployments repeatable
04  Build with security in mind
05  Monitor what you operate
06  Optimize for reliability and cost
07  Keep systems understandable
08  Continuously improve
```

---

## Let's Connect

I'm open to conversations around **DevOps, Cloud Engineering,
Cloud Infrastructure, CI/CD, Kubernetes, and automation opportunities.**

<div align="center">

### Dhiraj Dwivedi

**DevOps Engineer | Cloud Automation & CI/CD**

📧 **[dheerajd172@gmail.com](mailto:dheerajd172@gmail.com)**

💼 **LinkedIn:**
https://www.linkedin.com/in/dhiraj-dwivedi/

💻 **GitHub:**
https://github.com/DhirajCloud

</div>
