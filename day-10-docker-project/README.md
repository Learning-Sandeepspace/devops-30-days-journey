# Day 10 – Docker Project

## Objective
Build a custom Docker image using Nginx, run it locally, and push it to Docker Hub.

## Files
- Dockerfile – defines the image
- index.html – custom website

## Build Image
docker build -t sandeep-nginx:v1 .

## Run Container
docker run --name day10-nginx -d -p 8085:80 sandeep-nginx:v1

## Docker Hub
Image pushed to:
YOUR_USERNAME/sandeep-nginx:v1
