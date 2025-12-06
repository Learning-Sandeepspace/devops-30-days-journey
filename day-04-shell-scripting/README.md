# Day 04 – Shell Scripting (Automation Basics)

## Scripts Created
- `greet.sh` – prints a welcome message, date, and hostname.
- `intro.sh` – prints name and goal using variables and arguments.
- `user-info.sh` – accepts name and country as arguments and prints them.
- `check-number.sh` – checks if a number is greater than 10 and prints a message based on condition.
- `loop.sh` – loops over all files in the directory and prints their names.

## Concepts Practiced
- Shebang (`#!/bin/bash`)
- Using `echo` to print output
- Variables (`NAME="Sandeep"`)
- Positional arguments (`$1`, `$2`)
- If conditions (`if [ $1 -gt 10 ] ...`)
- For loops (`for f in *; do ...; done`)
- File permissions (`chmod +x`, `chmod 700`)
- Running scripts with `./script.sh`

## Hands-on Result
All scripts tested on an EC2 instance under `~/devops/day4` and executed successfully.
Screenshots of terminal output are stored inside the `screenshots/` folder.
