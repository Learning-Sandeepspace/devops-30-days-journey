# Day 08 – Containers Introduction

## What I Learned
- Difference between Virtual Machines and Containers.
- Why containers are lightweight and fast.
- Docker Architecture: Docker Engine, CLI, Images, Containers.
- Difference between Images vs Containers.
- How to run my first container.

## Commands Used
```bash
docker version
docker run hello-world
docker pull nginx
docker run nginx
docker run --name my-nginx -d -p 8080:80 nginx
