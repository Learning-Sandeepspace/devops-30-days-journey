# Day 03 – Linux Basics & Shell Scripting

## Concepts Practiced
- Navigating the filesystem (pwd, ls, cd)
- Creating files and directories (mkdir, touch)
- Viewing and modifying files (echo with > and >>, cat)
- Copying, moving, and renaming files (cp, mv)
- Deleting files and directories (rm, rm -r)
- File permissions and numeric modes (700, 744, 755)
- Making a shell script executable (chmod +x)
- Running a shell script

## Hands-on Work
- Created practice directory at `~/practice/day3` on EC2.
- Created and modified text files using `echo` with `>` and `>>`.
- Practiced file operations (cp, mv, rm).
- Set different permissions using `chmod 700`, `chmod 644`, `chmod +x`.
- Created `runme.sh` script to print:
  - Current date
  - Current user
  - Current working directory
  - Completion message

## Script Example
The `runme.sh` script:

- Prints today's date using `date`.
- Prints the username using `whoami`.
- Prints the current directory using `pwd`.
- Prints a final line: "Task B Complete".

## Screenshots
- EC2 terminal showing:
  - File operations
  - Permission changes
  - Successful `./runme.sh` output

Screenshots are stored in the `screenshots/` folder.
