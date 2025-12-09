# Day 07 Notes – Server Health Automation Script

## Commands Used on EC2
```bash
mkdir -p ~/devops-projects/day7-health-check
cd ~/devops-projects/day7-health-check
nano server-health.sh
chmod +x server-health.sh
./server-health.sh

What I Learned
	•	How to automate server health reports
	•	How to check CPU, RAM, Disk via Linux commands
	•	How to check service status with systemctl is-active
	•	How to log script output to /var/log/server-health.log
	•	How cron can automate the script every hourSave → exit.

---

