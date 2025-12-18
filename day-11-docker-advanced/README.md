# Day 11 – Docker Advanced

## Objective
Learn how to run Docker containers in a production-ready way by understanding lifecycle management, restart policies, networking, environment variables, and resource limits.

## Topics Covered
- Container lifecycle (run, start, stop, kill, restart, rm)
- Restart policies for production stability
- Environment variables
- Docker networking
- Resource limits (CPU & memory)
- Logs and container inspection

## Hands-on Summary
- Ran Nginx container with restart policy `unless-stopped`
- Verified restart policy using `docker inspect`
- Practiced stopping, killing, and restarting containers
- Created custom Docker network and tested container communication
- Applied memory and CPU limits to containers
- Used logs and inspect for debugging

## Key Learning
Containers are immutable. Any configuration change requires deleting and recreating the container.
