<div align="center">

# 🐳 Docker for AI & DevOps Engineering

**A complete, hands-on Docker course in 34 topics, from installation and Dockerfiles to volumes, multi-stage builds, Compose, AWS ECR/ECS, GitHub & GitLab CI/CD, networking, Swarm, secrets and monitoring.**

![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-Multi--container-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-ECR%20%7C%20ECS-FF9900?logo=amazonaws&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab-CI%2FCD-FC6D26?logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-RHEL%20%7C%20Ubuntu-FCC624?logo=linux&logoColor=black)

</div>

---

## 🎯 About this course

Practical Docker notes written while running every demo on a Linux VM: commands, real terminal output, diagrams and worked practical solutions, arranged in the order you should learn them.

---

## 📚 Course contents

### 🐳 Docker Fundamentals

| # | Topic |
|---|---|
| 01 | [Installing Docker and Docker Compose on RHEL 9](01.%20Installing%20Docker%20and%20Docker%20Compose%20on%20RHEL%209.md) |
| 02 | [Dockerfile and Docker Commands](02.%20Dockerfile%20and%20Docker%20Commands.md) |
| 03 | [BusyBox and Alpine Image Concepts](03.%20BusyBox%20and%20Alpine%20Image%20Concepts.md) |
| 04 | [Understanding and Creating a Dockerfile](04.%20Understanding%20and%20Creating%20a%20Dockerfile.md) |
| 05 | [Docker Pull and Push Commands](05.%20Docker%20Pull%20and%20Push%20Commands.md) |
| 06 | [Creating a Docker Image from a Container](06.%20Creating%20a%20Docker%20Image%20from%20a%20Container.md) |
| 07 | [Docker Daemon, Port Mapping and Conflicts](07.%20Docker%20Daemon%2C%20Port%20Mapping%20and%20Conflicts.md) |
| 08 | [Deploying an Application in Docker](08.%20Deploying%20an%20Application%20in%20Docker.md) |

### 🧪 Practicals I

| # | Topic |
|---|---|
| 09 | [Practical Phase 1 (Part 2) with Solutions](09.%20Practical%20Phase%201%20%28Part%202%29%20with%20Solutions.md) |
| 10 | [Practical Phase 2 with Solutions](10.%20Practical%20Phase%202%20with%20Solutions.md) |

### 💾 Storage & Volumes

| # | Topic |
|---|---|
| 11 | [Introduction to Docker Volumes](11.%20Introduction%20to%20Docker%20Volumes.md) |
| 12 | [Docker Volume Types Hands-On](12.%20Docker%20Volume%20Types%20Hands-On.md) |
| 13 | [Docker Image Variants and Changing the Default Docker Path](13.%20Docker%20Image%20Variants%20and%20Changing%20the%20Default%20Docker%20Path.md) |

### 🏗️ Building Images & Compose

| # | Topic |
|---|---|
| 14 | [Docker Multi-Stage Builds](14.%20Docker%20Multi-Stage%20Builds.md) |
| 15 | [Docker Compose Hands-On](15.%20Docker%20Compose%20Hands-On.md) |
| 16 | [Docker Data Containers](16.%20Docker%20Data%20Containers.md) |
| 17 | [Practical Phase 3 with Solutions](17.%20Practical%20Phase%203%20with%20Solutions.md) |
| 18 | [Dockerfile Keywords - RUN, ENV, ARG, CMD and ENTRYPOINT](18.%20Dockerfile%20Keywords%20-%20RUN%2C%20ENV%2C%20ARG%2C%20CMD%20and%20ENTRYPOINT.md) |

### ☁️ Registries & Cloud (AWS · GitHub · GitLab)

| # | Topic |
|---|---|
| 19 | [Pushing and Pulling Docker Images with AWS ECR](19.%20Pushing%20and%20Pulling%20Docker%20Images%20with%20AWS%20ECR.md) |
| 20 | [Deploying a Docker App to AWS ECS](20.%20Deploying%20a%20Docker%20App%20to%20AWS%20ECS.md) |
| 21 | [Pushing and Pulling Docker Images with GitHub and GitLab Registries](21.%20Pushing%20and%20Pulling%20Docker%20Images%20with%20GitHub%20and%20GitLab%20Registries.md) |

### 🔁 CI/CD Pipelines

| # | Topic |
|---|---|
| 22 | [Practical Phase 4 with Solutions](22.%20Practical%20Phase%204%20with%20Solutions.md) |
| 23 | [GitLab Workflow Automation with CI-CD Pipelines](23.%20GitLab%20Workflow%20Automation%20with%20CI-CD%20Pipelines.md) |
| 24 | [Pushing Images from GitLab to AWS ECR with CI-CD](24.%20Pushing%20Images%20from%20GitLab%20to%20AWS%20ECR%20with%20CI-CD.md) |
| 25 | [Building Images from GitHub to AWS ECR with CI-CD](25.%20Building%20Images%20from%20GitHub%20to%20AWS%20ECR%20with%20CI-CD.md) |

### 🌐 Networking

| # | Topic |
|---|---|
| 26 | [Introduction to Docker Networking](26.%20Introduction%20to%20Docker%20Networking.md) |
| 27 | [Docker Networking Hands-On](27.%20Docker%20Networking%20Hands-On.md) |
| 28 | [Linking Two Containers](28.%20Linking%20Two%20Containers.md) |

### 🛰️ Orchestration & Operations

| # | Topic |
|---|---|
| 29 | [Docker Swarm](29.%20Docker%20Swarm.md) |
| 30 | [Local Docker Registry](30.%20Local%20Docker%20Registry.md) |
| 31 | [Docker Monitoring](31.%20Docker%20Monitoring.md) |
| 32 | [Docker Secrets, Docker Stack and JBoss Deployment](32.%20Docker%20Secrets%2C%20Docker%20Stack%20and%20JBoss%20Deployment.md) |
| 33 | [Docker Aliases](33.%20Docker%20Aliases.md) |
| 34 | [Archiving Images and Containers](34.%20Archiving%20Images%20and%20Containers.md) |

---

## 🗂️ Repository structure

```
docker-for-ai-and-devops-engineering/
├── 01. … 34.  *.md          # One file per topic, in learning order
├── images/                  # Diagrams used in the topics
└── projects/
    ├── href-counter/        # Go app for multi-stage builds (topic 22, MIT licence © Alex Ellis)
    ├── gitlab-ci-nginx/     # GitLab CI/CD pipeline project (topic 23)
    └── github-actions-ecr/  # GitHub Actions → AWS ECR workflow (topic 25)
```

---

## 🚀 How to use it

1. Start with **topic 01** to install Docker on RHEL 9, then follow the topics in order.
2. Run every command on a Linux VM. The notes include the expected output.
3. Use the **Practical Phase** topics (09, 10, 17, 22) to test yourself.

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data and DevOps roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notes help you learn Docker, please star the repo. It helps other students find it!
