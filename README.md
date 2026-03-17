<div align="center">

<!-- Dynamic Typing Header -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Moamen+%F0%9F%91%8B;DevOps+%26+Security+Engineer;Building+Secure+Infrastructure;Future+DevSecOps+Founder" alt="Typing SVG" />

<br/>

<!-- Badges -->
<img src="https://img.shields.io/badge/Focus-DevOps-00D9FF?style=for-the-badge&logo=shield&logoColor=white" />
<img src="https://img.shields.io/badge/Location-Cairo%2C+Egypt-FF6B6B?style=for-the-badge&logo=googlemaps&logoColor=white" />
<img src="https://img.shields.io/badge/Open+To-Freelance%20%26%20Collaboration-22C55E?style=for-the-badge&logo=handshake&logoColor=white" />

</div>

---

## `whoami`

```yaml
name: Moamen Lotfy
role: DevOps Engineer → Senior DevSecOps (in progress)
location: Cairo, Egypt
mission: >
  Designing reliable, scalable, and automated infrastructure
  to support modern software systems.
currently:
  - Deepening expertise in Docker & Kubernetes for production-grade deployments
  - Freelancing on advanced DevOps projects (Mostaqel platform)
  - Developing a portfolio & website showcasing DevOps projects
  - Preparing for: AWS SAA-C03 | CKA | Terraform
mindset: "Automation and reliability are the pillars of modern infrastructure."
```

---

## 🛠️ Tech Stack

<div align="center">

### ⚙️ Infrastructure & Orchestration
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### ☁️ Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

### 🔒 Security & Monitoring
![Security](https://img.shields.io/badge/DevSecOps-FF4B4B?style=for-the-badge&logo=shield&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

### 💻 Languages & Scripting
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🗂️ [AutoCloud To-Do — Full Stack DevOps Deployment](https://github.com/MomenLotfy/DEPI-Final-Project)
> Comprehensive DevOps pipeline for a **task management application**  
> Automates AWS infrastructure provisioning, environment setup, and production-ready Kubernetes deployment  
> Full lifecycle management using **Terraform**, **Ansible**, **Jenkins**, **Kubernetes**, **Helm**, and **ArgoCD**  
> `Terraform` `Ansible` `Jenkins` `Kubernetes` `Helm` `ArgoCD` `Docker` `AWS`

---

## 📁 Projects & Labs Breakdown

| Project | Stack | Type | Status |
|---|---|---|---|
| 🗂️ AutoCloud To-Do | Terraform · Ansible · Jenkins · K8s · ArgoCD | DevOps Pipeline | ✅ Complete |
| 🐳 Task Manager App | Docker · Flask · Nginx · PostgreSQL · Redis | Docker Lab | ✅ Complete |
| ☸️ K8s Deployment Lab | Kubernetes · Blue-Green · emptyDir | K8s Lab | ✅ Complete |
| 🏗️ K8s Multi-Tenancy | Namespaces · RBAC · Resource Quotas | K8s Lab | ✅ Complete |
| 💬 Chatwoot Self-Hosted | Docker · Nginx · PostgreSQL · Redis | Freelance | 🔄 Active |
| 🌐 Laravel / Next.js Isolation | Docker · Multi-env · Nginx | Freelance | 🔄 Active |
| 📋 Mini Task Manager (Bash) | Bash · Linux · CRUD | Scripting Project | ✅ Complete |
| 🌍 Portfolio Website | HTML · CSS · JS · GitHub Pages | Personal | 🔄 Ongoing |

---

## 🏗️ Infrastructure Architecture — Task Manager App

```
                        ┌─────────────────────────────────────┐
                        │         Docker Network              │
                        │                                     │
         HTTP           │   ┌──────────┐                      │
   ──────────────────►  │   │  Nginx   │  Reverse Proxy       │
                        │   │ :80/:443 │                      │
                        │   └────┬─────┘                      │
                        │        │                            │
                  ┌─────┼────────┼────────────────┐           │
                  │     │        │                │           │
                  ▼     │        ▼                ▼           │
            ┌─────────┐ │  ┌──────────┐   ┌──────────┐       │
            │Flask App│ │  │Flask App │   │Flask App │       │
            │(web:1)  │ │  │(web:2)   │   │  (api)   │       │
            └────┬────┘ │  └────┬─────┘   └────┬─────┘       │
                 │      │       │               │             │
                 └───────────────┬──────────────┘             │
                        │        │                            │
                        │   ┌────┴──────┐  ┌──────────┐      │
                        │   │PostgreSQL │  │  Redis   │      │
                        │   │  :5432    │  │  :6379   │      │
                        │   └───────────┘  └──────────┘      │
                        └─────────────────────────────────────┘
```

---

## 📈 My DevOps Journey

```
2023 ──────────────────────────────────────────────────────────► Now

  [Q1 2023]           [Q2-Q3 2023]         [Q4 2023]         [2024-Now]
      │                    │                    │                  │
  Networking &         Linux &              Docker &           Kubernetes
  Fundamentals         Bash                 Jenkins            + AWS + K8s
      │                    │                    │                  │
  ┌───┴───┐           ┌────┴────┐          ┌────┴────┐        ┌────┴────┐
  │ OSI   │           │ Bash    │          │ Docker  │        │  K8s    │
  │ TCP/IP│           │ Scripts │          │ Labs    │        │  Labs   │
  │ Subn. │           │ Linux   │          │ Compose │        │ Helm    │
  └───────┘           │ Admin   │          │ Nginx   │        │ ArgoCD  │
                      └─────────┘          └─────────┘        │ DevSecOps│
                                                               └─────────┘
                                                               🎯 CURRENT
```

---

## 💼 Freelance Work

> Currently taking on **DevOps projects** via the **Mostaqel platform**

| Client Project | Description | Key Deliverables |
|---|---|---|
| 🏢 Chatwoot Production | Self-hosted high-volume messaging platform | Docker Compose · Nginx SSL · PostgreSQL · Redis · Monitoring |
| 🌐 Laravel/Next.js Multi-Env | Isolated staging & production environments | Docker Multi-env · Nginx routing · Zero-downtime deploys |

**What I offer as a freelancer:**
- 🐳 Containerization & Docker Compose setup
- ☸️ Kubernetes cluster deployment (K3s/K8s)
- 🔧 CI/CD pipeline design (Jenkins / GitHub Actions)
- 📊 Monitoring setup (Prometheus + Grafana)
- 🔒 Basic security hardening & SSL/TLS configuration
- 📄 Full technical documentation & README

---

## 🔐 Security Focus Areas

```
DevSecOps Pipeline Security
├── 🔍 SAST (Static Application Security Testing)
├── 🐳 Container Image Scanning (Trivy / Grype)
├── 🔑 Secrets Management (Vault / env hardening)
├── 📋 RBAC & Least Privilege (Kubernetes)
├── 🔒 Network Policies & Pod Security
└── 🛡️ Infrastructure Hardening (CIS Benchmarks)

CI/CD Security Gates
├── Pre-commit hooks
├── Dependency vulnerability checks
├── Image signing & verification
└── Policy-as-Code (OPA / Kyverno)
```

---

## 🎯 Certifications Roadmap

```
[ IN PROGRESS ]

  ⬜  AWS Solutions Architect Associate (SAA-C03)
  ⬜  Certified Kubernetes Administrator (CKA)
  ⬜  GitHub Foundations
  ⬜  DevSecOps Professional

  ✅  Docker Advanced 
  ✅  Kubernetes Fundamentals & Deployments 
  ✅  Jenkins CI/CD 
  ✅  Linux & Bash Scripting 
```

---

## 🤝 How I Work

```bash
$ cat working_principles.txt

1. Document everything — if it's not written, it didn't happen
2. Automate before you repeat — manual steps are future bugs
3. Security is not a phase — it's built in from day zero
4. Version control everything — infrastructure, configs, scripts
5. Monitor proactively — alerts before the client notices
6. Communicate clearly — technical work needs readable outputs
```

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=MomenLotfy&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MomenLotfy&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=MomenLotfy&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=FFFFFF&sideLabels=FFFFFF&dates=888888" />

</div>

---

## 🌱 Currently Learning

```bash
$ kubectl get learning --all-namespaces

NAMESPACE           NAME                             STATUS      PROGRESS
certifications      GitHub Foundations               Running      ██████░░░░  60%
certifications      AWS Solutions Architect (SAA-C03) Running     ████████░░  80%
certifications      Certified Kubernetes Admin (CKA)  Running     ██████░░░░  60%
freelance           AutoCloud To-Do Deployment        Active      ██████████  100%
freelance           Multi-Env Laravel / Next.js       Active      ██████░░░░  70%
company-vision      Cloud Infrastructure Strategy     Planning    ███░░░░░░░  30%
company-vision      DevOps Tooling Automation         Planning    ███░░░░░░░  25%
company-vision      Security Monitoring Setup         Planning    ████░░░░░░  40%
```

---

## 📚 Resources I Learn From

| Area | Resources |
|---|---|
| 🐳 Docker | KodeKloud · Docker Official Docs · Nigel Poulton's Book |
| ☸️ Kubernetes | KodeKloud · Kubernetes.io · TechWorld with Nana |
| ☁️ AWS | Stephane Maarek (Udemy) · AWS Official Docs · ExamPro |
| 🔒 DevSecOps | OWASP · Linux Foundation · CloudSecDocs |
| 🛠️ Terraform | HashiCorp Learn · Zeal Vora (Udemy) |
| 📋 General | DevOps Roadmap · GitHub Repos · Medium Engineering Blogs |

---

## 💡 Vision

> *"Most people secure their apps after building them. I want to build security in from day zero — and help others do the same."*
>
> — Working toward founding a **software security services company** inspired by the SecAlign model:  
> delivering DevSecOps consulting, infrastructure hardening, and CI/CD security pipelines for modern teams.

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/momendevops/)
<a href="mailto:momen.elpesa123@gmail.com">
  <img src="https://img.shields.io/badge/Email-Reach+Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit+Site-00D9FF?style=for-the-badge&logo=vercel&logoColor=white)](https://momenlotfy.github.io/Mo-Ops/)

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=MomenLotfy&color=00D9FF&style=for-the-badge&label=PROFILE+VIEWS" />

*"Automate everything. Secure everything. Document everything."*

</div>
