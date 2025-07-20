# 🐳 Dockerized Django Notes App

> **Disclaimer:** This project is **not originally created by me**. I found it online and I'm using it only for learning purposes related to Docker, Docker Compose, and deployment using Nginx & MySQL.

## 📚 Purpose

I wanted to understand how to:

- Dockerize a Django application
- Connect Django with MySQL using Docker Compose
- Use Nginx as a reverse proxy
- Deploy a 3-tier web application

## 📦 Tech Stack

- **Django** (Backend)
- **MySQL** (Database)
- **Docker & Docker Compose**
- **Nginx** (Web server / reverse proxy)

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/mohibali03/django-notes-app.git
   cd django-notes-app
2. Run Docker Compose
   ```bash
   docker compose up --build
3. Access the App
   ```bash
   http://<ec2_public_ip>/
