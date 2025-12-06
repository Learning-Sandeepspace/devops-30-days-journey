# Day 04 Notes – Shell Scripting Practice

## Files and Scripts
- `greet.sh` – first script with echo, date, hostname.
- `intro.sh` – used variables and later positional arguments.
- `user-info.sh` – practiced `$1` and `$2`.
- `check-number.sh` – used `if [ $1 -gt 10 ]` structure.
- `loop.sh` – used `for f in *` loop.

## Key Commands
```bash
mkdir -p devops/day4
cd devops/day4

nano greet.sh
chmod 700 greet.sh
./greet.sh

nano intro.sh
chmod 700 intro.sh
./intro.sh

nano user-info.sh
chmod 700 user-info.sh
./user-info.sh Sandeep india

nano check-number.sh
chmod 700 check-number.sh
./check-number.sh 5
./check-number.sh 25

touch one.txt two.txt three.txt
nano loop.sh
chmod +x loop.sh
./loop.sh
