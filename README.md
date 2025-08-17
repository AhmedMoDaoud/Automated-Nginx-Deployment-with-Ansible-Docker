# 🚀 Automated Nginx Deployment with Ansible & Docker

This project demonstrates how to use **Ansible** to automate the deployment of an **Nginx web server** inside a **Docker container** on an **AWS EC2 Ubuntu instance**.  

---

## 📌 Project Overview
- Provision and configure an EC2 Ubuntu server.
- Install Docker automatically via Ansible.
- Deploy and run an **Nginx container** with port `80` exposed.
- Verify successful deployment by testing HTTP response with `curl`.

---

## ⚙️ Features
- Infrastructure as Code using **Ansible**.
- Automated installation of required packages (`docker.io`, `curl`).
- Service management to ensure Docker is always running.
- Deployment of a containerized **Nginx web server**.
- Automated verification of the web server availability.

---

## 🛠️ Tech Stack
- **Ansible** (automation & configuration management)  
- **Docker** (containerization)  
- **AWS EC2 Ubuntu** (cloud infrastructure)  
- **Nginx** (web server)  

---

## ▶️ How to Run
1. Configure your Ansible inventory with the target EC2 instance:
   ```ini
   [EC2_Ubuntu]
   ec2-instance ansible_host=<EC2_PUBLIC_IP> ansible_user=ubuntu ansible_ssh_private_key_file=~/.ssh/your-key.pem
## 👤 Author
**Ahmed Mohamed Daoud**  
- IT Specialist | Network Engineer | DevOps Enthusiast  
- [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/AMD971126)
