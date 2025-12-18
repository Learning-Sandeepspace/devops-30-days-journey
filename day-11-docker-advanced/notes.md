# Day 11 Notes – Docker Advanced

## Container Lifecycle
- docker run → create + start container
- docker start → start existing container
- docker stop → graceful shutdown (SIGTERM)
- docker kill → force shutdown (SIGKILL)
- docker restart → stop + start
- docker rm -f → force remove container

## Restart Policy
- Restart policy is applied at container creation time
- Cannot be modified later
- Common policies:
  - no (default)
  - always
  - unless-stopped
  - on-failure

## Environment Variables
- Passed at runtime using `-e`
- Keeps configuration separate from image
- Image = code, Env vars = config

## Docker Networking
- Containers communicate using names
- No IP hardcoding required
- Docker provides internal DNS

## Resource Limits
- --memory limits RAM usage
- --cpus limits CPU usage
- Prevents one container from crashing the server

## Debugging
- docker logs → view application logs
- docker inspect → full container configuration
- docker stats → live CPU & memory usage
