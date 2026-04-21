# ⏰ Automated Backup System using Cron

## 🎯 Overview
This project demonstrates automated backups using cron jobs in Linux.

---

## 🟢 📁 PROJECT STRUCTURE
linux-backup-cron-project/
│
├── README.md
├── backup.sh
├── screenshots/
│   ├── script.png
│   ├── output.png
│   ├── cron.png

---

## ⚙️ Script
#!/bin/bash
tar -czvf /backup/project_$(date +%F).tar.gz /project

---

## ⏰ Cron Job
0 2 * * * /backup.sh

---

## 📸 Screenshots
![Script] ==> (screenshots/script.png)
![Output] ==> (screenshots/output.png)
![Cron] ==> (screenshots/cron.png)
---

## 🚀 Result
Daily automatic backups successfully configured.

---

## 🟢 💻 FULL GIT WORKFLOW (GITHUB + GITLAB)

## 📁 Step 1
cd ~/OneDrive/Desktop/project4

## ⚙️ Step 2
git init
git branch -M main

## 📦 Step 3
git add .
git commit -m "Project 4: Automated backup with cron"

## 🔗 GITHUB
git remote add github https://github.com/Abdullahaiops9-glt/linux-backup-cron-project
git push github main

👉 Use GitHub token as password

## 🔗 GITLAB
git remote add gitlab https://gitlab.com/abdullahaiops9/linux-backup-cron-project
git push gitlab main
