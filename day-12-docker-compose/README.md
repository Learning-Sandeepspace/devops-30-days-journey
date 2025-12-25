# Day 12 – Docker Compose

## Objective
Use Docker Compose to run and manage multiple containers with a single YAML file.

## What I Built
A 2-service Compose setup:
- web (nginx) on http://localhost:8086
- api (nginx) on http://localhost:8087

## Key Concepts
- services: define multiple containers
- ports: publish host ports
- restart: production stability
- automatic networking: services communicate by name

## Commands Used
docker compose up -d
docker compose ps
docker compose logs --tail=20
docker compose down

## Networking Test
docker exec -it day12-web ping -c 2 api
