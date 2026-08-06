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