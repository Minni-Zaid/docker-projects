<<<<<<< HEAD
# 🐳 Docker Static Website

A simple static website containerized using Docker and served using Nginx.

## 🚀 Project Overview

In this project, I containerized a basic HTML and CSS website using Docker.

Nginx is used as the web server inside the Docker container.

The website is accessed locally through:

http://localhost:8080

## 🛠️ Technologies Used

- HTML
- CSS
- Docker
- Nginx

## 📂 Project Structure

```text
Docker-Static-Website/
│
├── index.html
├── style.css
├── Dockerfile
├── README.md
├── commands.md
├── notes.md
└── screenshots/
    ├── 01-docker-build.png
    ├── 02-docker-images.png
    ├── 03-docker-ps.png
    ├── 04-website.png
    ├── 05-docker-logs.png
    └── 06-docker-inspect.png
=======
# Docker Nginx Web Server

## 📌 Project Overview

This project demonstrates how to run an Nginx web server using Docker.

It is my first Docker mini project where I learned how to:

- Pull Docker images
- Run Docker containers
- Map ports
- View running containers
- Inspect container details
- View logs
- Stop and remove containers

---

## 🛠 Technologies Used

- Docker Desktop
- Docker CLI
- Nginx
- Windows 11
- WSL Ubuntu

---

## 🚀 Commands Used

```bash
docker pull nginx
docker run -d --name my-nginx -p 8080:80 nginx
docker ps
docker images
docker logs my-nginx
docker inspect my-nginx
docker stop my-nginx
docker start my-nginx
docker rm -f my-nginx
```

---

## 🌐 Output

Open your browser:

http://localhost:8080

You should see:

Welcome to nginx!

---

## 📷 Screenshots

Screenshots are available in the `screenshots` folder.

---

## 📚 What I Learned

- Docker Image vs Container
- Port Mapping
- Running Containers
- Docker Logs
- Docker Inspect
- Container Lifecycle
>>>>>>> 2f9d5c82a53a5a88f0b9fbbca1cc8f183842f7b6
