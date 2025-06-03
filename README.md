# Yii2 + Docker Swarm + CI/CD + Ansible Deployment

## 🔧 Technologies
- Yii2 PHP App
- Docker & Docker Swarm
- GitHub Actions
- Ansible
- NGINX (host-level reverse proxy)

## 🚀 Setup Instructions

### Prerequisites:
- AWS EC2 Ubuntu Server
- Docker Hub Account
- GitHub Repo

### 1. Ansible Setup
```bash
cd ansible
ansible-playbook -i inventory playbook.yml

