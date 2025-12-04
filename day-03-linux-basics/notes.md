# Day 03 Notes – Linux Basics & Shell Scripting

## Commands Practiced
```bash
# Navigate and setup
mkdir -p devops/day3
cd devops/day3
pwd

# File creation and editing
touch linux-basics.txt
echo "Linux day-3 - practice" > linux-basics.txt
echo "This is my second line" >> linux-basics.txt
cat linux-basics.txt

# Copy, rename, delete
cp linux-basics.txt backup-linux-basics.txt
mv linux-basics.txt main-notes.txt
rm backup-linux-basics.txt

# Permissions
ls -l main-notes.txt
chmod 700 main-notes.txt
ls -l main-notes.txt

# Script creation
touch welcome.sh
nano welcome.sh
chmod +x welcome.sh
./welcome.sh

# Practice area
mkdir -p ~/practice/day3
cd ~/practice/day3
mkdir scripts logs temp

# Files with specific permissions
touch secret.txt public.txt runme.sh
chmod 700 secret.txt
chmod 644 public.txt
chmod +x runme.sh
./runme.sh
