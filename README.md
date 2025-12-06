# SecureBank

[![Docker](https://img.shields.io/badge/Docker-Ready-blue?logo=docker)](https://www.docker.com/)
[![.NET](https://img.shields.io/badge/.NET-6-blue?logo=dotnet)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/License-Original-green)](https://github.com/ssrdio/SecureBank)

## 📘 Overview

SecureBank is a vulnerable .NET/C# training application designed for students, penetration testers, and web developers who want to learn Web Application Penetration Testing (WAPT).

This version of SecureBank is a forked and modified version of the original project created by **Leonardo Tamiano (ssrdio)**.  
All credit for the original concept, source structure, and initial development goes to him.

📌 Original Repository:  
https://github.com/ssrdio/SecureBank

### 🔧 This modified version includes:
- UI and styling improvements  
- Additional vulnerabilities added for learning  
- Minor fixes and enhancements  
- Dockerized for easy local deployment  

---

## 🐳 Deployment Using Docker

### 1️⃣ Install Docker
 
```bash
sudo apt update && sudo apt install -y docker.io
sudo systemctl enable docker
sudo systemctl start docker
### 2️⃣ Install Docker Compose
sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" \
  -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose
docker-compose --version
3️⃣ Run SecureBank
cd secure-bank
sudo docker-compose up -d
Check containers:

sudo docker container ps

🌐 Accessing SecureBank

Open:

http://localhost:1337

🔑 Default Credentials
Username: admin@hexdump.sh
Password: admin

🎯 Purpose

This project is intended only for learning, including:

OWASP Top 10

Web Application Penetration Testing

Vulnerability identification training

⚠️ Not for production
⚠️ Do not expose publicly
