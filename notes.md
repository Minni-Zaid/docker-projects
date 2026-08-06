# Docker Nginx Web Server Notes

## What is Docker?

Docker is a containerization platform used to build, package, and run applications consistently on any system.

---

## What is an Image?

An Image is a read-only template used to create containers.

Example:
Nginx Image

---

## What is a Container?

A Container is a running instance of an Image.

Image → Container

---

## What is Docker Hub?

Docker Hub is an online repository that stores Docker images.

Website:
https://hub.docker.com

---

## What is Nginx?

Nginx is a high-performance web server.

It is commonly used for:

- Hosting websites
- Reverse Proxy
- Load Balancer
- API Gateway

---

## What is Port Mapping?

Example:

8080:80

8080 → Host Port

80 → Container Port

Browser:

http://localhost:8080

---

## Docker Workflow

Docker Hub
↓

Docker Image
↓

Docker Container
↓

Application Running

---

## What I Learned

✔ Docker Installation

✔ Docker Images

✔ Docker Containers

✔ Pull Image

✔ Run Container

✔ Port Mapping

✔ Docker Logs

✔ Docker Inspect

✔ Stop Container

✔ Remove Container

---

## Interview Question

Q: What is Docker?

Answer:

Docker is an open-source containerization platform used to package applications with all dependencies and run them consistently across different environments.

---

Q: Difference between Image and Container?

Image:
Blueprint

Container:
Running instance of an Image

---

Q: Why do we use Nginx?

To host websites and act as a web server, reverse proxy, and load balancer.