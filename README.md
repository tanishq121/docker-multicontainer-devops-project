# 🚀 Dockerized Multi-Container Application Deployment on AWS

## 📌 Project Overview

This project demonstrates a production-style deployment of a multi-container application using Docker, Docker Compose, Nginx Reverse Proxy, AWS EC2, and SSL/TLS.

The objective of this project was to gain hands-on experience with containerization, service orchestration, reverse proxy configuration, cloud deployment, and secure web hosting.

---

## 🏗 Architecture

```text
Internet
    │
    ▼
tanishqgupta.fun
    │
    ▼
Nginx Reverse Proxy
 ┌────┴────┐
 ▼         ▼
Frontend   Backend API
              │
              ▼
           MySQL
```

---

## 🛠 Technologies Used

* Docker
* Docker Compose
* Nginx
* AWS EC2
* Linux
* MySQL
* Python Flask
* Git & GitHub
* SSL/TLS

---

## 📂 Project Structure

```text
docker-multicontainer-devops-project/
│
├── README.md
├── docker-compose.yml
│
├── frontend/
│   ├── index.html
│   └── Dockerfile
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── nginx/
│   └── default.conf
│
└── screenshots/
```

---

## ✨ Features

* Multi-container architecture
* Dockerized frontend application
* Dockerized backend API
* Nginx reverse proxy configuration
* AWS EC2 deployment
* Custom domain integration
* SSL/TLS secured communication
* Docker networking
* Service orchestration using Docker Compose

---

## 🚀 Deployment Steps

### Clone Repository

```bash
git clone https://github.com/your-username/docker-multicontainer-devops-project.git
cd docker-multicontainer-devops-project
```

### Build Containers

```bash
docker-compose build
```

### Start Services

```bash
docker-compose up -d
```

### Verify Running Containers

```bash
docker ps
```

### Verify Services

```bash
docker-compose ps
```

---

## 🔐 Security

* HTTPS enabled using SSL/TLS certificates
* Nginx reverse proxy for request routing
* Container isolation through Docker networking
* Secure cloud deployment practices

---

## 🎯 Learning Outcomes

Through this project I learned:

* Docker image creation and management
* Multi-container deployments
* Docker Compose orchestration
* Container networking
* Reverse proxy implementation with Nginx
* AWS cloud deployment
* SSL/TLS certificate management
* Linux server administration
* GitHub project documentation

---

## 👨‍💻 Author

**Tanishq Gupta**

DevOps & Cloud Computing Enthusiast

### Skills

Linux • AWS • Docker • Git • Nginx • Bash • Cloud Infrastructure

GitHub: https://github.com/tanishq121

LinkedIn: https://www.linkedin.com/in/tanishqgupta-devops
