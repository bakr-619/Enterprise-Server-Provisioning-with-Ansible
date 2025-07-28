
# 🚀 Enterprise Server Provisioning with Ansible

Welcome to a sleek, automated server provisioning solution built with **Ansible**! This repo showcases my DevOps prowess, automating enterprise-grade server setup with SSH key-based authentication. It checks OS/time, spins up Nginx, handles file operations, and generates a slick report with Jinja—crafted to impress! 💻

Built by **Abu Bakkar**, a Cloud Engineer with 1 year in Python/Django and 4 months rocking AWS, Terraform, and GitHub Actions from my hotel/finance project. Fresh from debugging CI/CD and Nginx, this is my DevOps vibe! 🌟

## 🎯 Task Breakdown
- 🔑 **Secure Auth**: SSH keys for rock-solid access.
- 🖥️ **Server Checks**: OS name/version, control/remote time.
- 🌐 **Nginx Setup**: Install and auto-start Nginx like a pro.
- 📂 **File Ops**: Download file from GitHub, create `task/devops-bootcamp/week3/ansible`, copy to remote server, verify it’s there.
- 📊 **Report**: Generate `<timestamp>_server_mgmt.txt` with OS, times, and file status using Jinja.

## 🛠️ Setup Guide
1. **Prep Your Environment**:
   - Control node: Ubuntu VM with Ansible (`sudo apt install ansible`).
   - Remote server: Ubuntu with SSH enabled.
   - SSH keys: Run `ssh-keygen -t rsa -b 4096`, then `ssh-copy-id <remote-user>@<remote-server-ip>`.

2. **Clone the Repo**:
   ```bash
   git clone https://github.com/bakr-619/ansible-task.git
   cd ansible-task
