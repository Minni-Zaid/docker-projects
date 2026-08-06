# Docker Commands

## Check Docker Version

```bash
docker --version
```

Purpose:
Checks the installed Docker version.

---

## Docker Information

```bash
docker info
```

Purpose:
Displays Docker Engine information.

---

## Pull Nginx Image

```bash
docker pull nginx
```

Purpose:
Downloads the Nginx image from Docker Hub.

---

## View Images

```bash
docker images
```

Purpose:
Lists downloaded Docker images.

---

## Run Nginx Container

```bash
docker run -d --name my-nginx -p 8080:80 nginx
```

Purpose:
Runs an Nginx container in detached mode.

---

## View Running Containers

```bash
docker ps
```

Purpose:
Shows all running containers.

---

## View All Containers

```bash
docker ps -a
```

Purpose:
Shows running and stopped containers.

---

## View Logs

```bash
docker logs my-nginx
```

Purpose:
Displays container logs.

---

## Inspect Container

```bash
docker inspect my-nginx
```

Purpose:
Shows complete container details.

---

## Stop Container

```bash
docker stop my-nginx
```

Purpose:
Stops a running container.

---

## Start Container

```bash
docker start my-nginx
```

Purpose:
Starts a stopped container.

---

## Restart Container

```bash
docker restart my-nginx
```

Purpose:
Restarts the container.

---

## Remove Container

```bash
docker rm my-nginx
```

Purpose:
Deletes the container.

---

## Remove Image

```bash
docker rmi nginx
```

Purpose:
Deletes the Docker image.

---

## Execute Commands Inside Container

```bash
docker exec -it my-nginx bash
```

Purpose:
Opens a shell inside the container.