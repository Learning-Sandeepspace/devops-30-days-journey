# Notes – Day 08

## Key Concepts
- Containers share host OS kernel.
- VMs have full OS – containers do not.
- Images = blueprint, Containers = running instance.

## Important Flags
- `-d` = detached mode
- `-p host:container` = port mapping
- `--name` = assign custom container name

## What I Observed
- hello-world container exits immediately after printing the message.
- nginx container continues running in background using `-d`.
