# Day 12 Notes – Docker Compose

## Why Compose
- Avoid long docker run commands
- One file describes the whole app stack
- Easy to start/stop multi-container setups

## Important Commands
- docker compose up -d  -> start stack
- docker compose ps     -> service status
- docker compose logs   -> logs for all services
- docker compose down   -> stop and remove stack

## Ports
- "8086:80" means host 8086 -> container 80

## Networking
- Compose creates a default network
- Services can reach each other using service names (DNS)
