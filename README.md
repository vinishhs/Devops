# 🚀 DevOps Training Summary

## 🎯 Aim
To gain practical knowledge of modern DevOps practices by working with essential tools and understanding how development, automation, and deployment integrate in real-world environments.

## 🛠️ Tools & Technologies Covered
- Linux (Ubuntu, WSL)
- Git & GitHub
- Docker
- Jenkins (CI/CD)
- AWS (EC2, Apache/Nginx)
- Ansible
- Terraform
- Kubernetes
- Prometheus

---

## 📅 Day-wise Activities

### 📅 Day 1 – Linux Basics, Virtualization & Commands
- Installed Ubuntu using VMware, explored virtualization concepts.
- Learned benefits of WSL for developers.
- Practiced essential commands: `pwd`, `ls`, `cd`, `mkdir`, `rmdir`, `touch`, `cp`, `mv`, `rm`, `cat`, `grep`, `find`, `chmod`.
- Managed packages: `sudo apt update`, `sudo apt upgrade`, `sudo apt install`.
- Worked with file permissions, user roles, and the `vi` editor.
- Discussed Long Term Support (LTS) releases.

---

### 🐳 Day 2 – Docker & GitHub Setup
- Understood containers vs virtual machines.
- Built Docker images and ran containers with port mapping.
- Practiced: `docker build`, `docker run`, `docker ps`, `docker stop`.
- Pushed images to Docker Hub.
- Initialized Git repository, committed code, and pushed to GitHub.
- Learned merge conflicts and resolution.

---

### 🔁 Day 3 – Git Workflow & Jenkins Introduction
- Improved Git knowledge: branching, merging, `git log`, `git status`.
- Pushed projects from Ubuntu to GitHub.
- Introduction to CI/CD principles.
- Installed Java and Jenkins.
- Understood Jenkins automation for build & deployment.

---

### ⚙️ Day 4 – Jenkins Configuration & Pipeline
- Configured Jenkins server and accessed via browser.
- Created Freestyle jobs and connected with GitHub.
- Learned build triggers: manual, poll SCM, webhooks.
- Installed Git & Docker plugins.
- Created pipeline stages: **Clone → Build → Test → Deploy**.
- Introduction to cron scheduling.

---

### ☁️ Day 5 – AWS EC2 & Deployment Practice
- Created Ubuntu & Windows EC2 instances.
- Used key pairs for secure login.
- Connected via SSH and Remote Desktop.
- Installed Apache/Nginx and hosted sample web pages.
- Pulled project files from GitHub.
- Learned cost management by stopping/terminating instances.

---

### 🔧 Day 6 – Automation with Ansible & Terraform
- Understood DevOps flow: **Code → Build → Provision → Configure → Deploy**.
- Configured Jenkins credentials for GitHub.
- Installed Ansible, created inventory files, verified connectivity.
- Executed playbooks for package installation.
- Practiced Terraform commands: `init`, `validate`, `plan`, `apply`, `destroy`.
- Discussed distributed system architecture and worker management.

---

## ☸️ Kubernetes & Prometheus – DevOps Essentials

### Kubernetes – Container Orchestration
- Provides automatic deployment, self-healing, scaling, load balancing, rolling updates.
- Core objects: **Cluster, Node, Pod, Service, Deployment**.
- Benefits: reliability, reduced manual ops, better resource utilization.

### Prometheus – Monitoring & Alerting
- Collects metrics as time-series data.
- Key capabilities: infrastructure monitoring, performance tracking, PromQL queries, visualization integration, real-time alerting.
- Important elements: **Metrics, Targets, Alertmanager**.
- Role in DevOps: ensures system health and quick failure response.

---

## 🧠 Master–Worker Architecture
- **Master/Control Node** → Plans and manages tasks.
- **Workers/Agents** → Execute assigned operations.
- Used in Jenkins, Kubernetes, and distributed systems.

---

## 📝 Conclusion
Across six days of intensive hands-on sessions, strong foundational knowledge of DevOps practices was established.

### Key Achievements
✔ Comfortable working in Linux environments  
✔ Creating and managing Docker containers  
✔ Using Git & GitHub for collaboration  
✔ Automating CI/CD pipelines via Jenkins  
✔ Deploying applications in AWS  
✔ Configuring infrastructure with Ansible  
✔ Provisioning resources using Terraform  
✔ Understanding container orchestration and monitoring  

This journey provided practical exposure to how modern software moves from development to production efficiently and reliably.
