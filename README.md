# 🍰 Cake Shop Frontend (Dockerized)

A beautiful and responsive Cake Shop frontend built using **HTML & CSS**, containerized using **Docker** for easy deployment.

## 🚀 Project Overview

This project is a simple static cake shop website that showcases different cakes with a modern UI design.  
It is designed to demonstrate **frontend development + containerization skills**.

## ✨ Features

- 🎨 Clean and modern UI
- 📱 Responsive design (mobile-friendly)
- 🍰 Cake product showcase
- 🐳 Dockerized for easy deployment
- ⚡ Lightweight and fast

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- Docker  

## 📂 Project Structure
cake-shop/   
│── index.html   
│── Dockerfile   
│── README.md   

## 🐳 Docker Setup

### 1. Build Docker Image

```bash
docker build -t cake-shop .

```
### Run Container
```bash
docker run -d -p 8080:80 cake-shop

```

### Open in Browser

http:// < Public-IP-AWS-ec2 > :8080
