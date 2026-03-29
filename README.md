# OSSCapstoneProject
# Open Source Software Audit — Python

## 👤 Student Details
- Name: Adit Chaudhary  
- Roll Number: 24BCE10767
- Course: Open Source Software  
- University: VIT Bhopal University  

---

## 🐍 Chosen Software
**Python**

Python is an open-source programming language known for its simplicity, readability, and wide range of applications such as web development, data science, automation, and artificial intelligence.

---

## 📂 Project Contents

This repository contains:
- 5 Shell Scripts (.sh files)
- Project Report (PDF)
- README.md file

---

## 💻 Scripts Description

### 🔹 Script 1 — System Identity Report
Displays system information such as:
- Linux distribution
- Kernel version
- Logged-in user
- Uptime and date  
This script acts as a basic system overview tool.

---

### 🔹 Script 2 — FOSS Package Inspector
Checks whether Python is installed on the system and displays package details. It also prints a short description of the package using a case statement.

---

### 🔹 Script 3 — Disk and Permission Auditor
Analyzes important directories and shows:
- Disk usage
- File permissions
- Owner and group details  
It also checks the Python directory.

---

### 🔹 Script 4 — Log File Analyzer
Reads a log file and:
- Counts occurrences of a keyword (default: "error")
- Displays the last 5 matching lines  
Useful for basic log analysis.

---

### 🔹 Script 5 — Open Source Manifesto Generator
Takes user input and generates a personalized open-source philosophy statement, which is saved to a text file.

---

## ⚙️ Requirements

- Linux Operating System (Ubuntu recommended)
- Bash Shell
- Basic Linux commands

---

## ▶️ How to Run the Scripts

Step 1: Open Terminal and go to project folder
```bash
cd oss_project

Step 2: Give execution permission
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

Step 3: Run scripts
Script 1:
./script1.sh
Script 2:
./script2.sh
Script 3:
./script3.sh
Script 4:
./script4.sh /var/log/syslog error
Script 5:
./script5.sh
