# Open Source Software Audit — Python

## 👤 Student Details
- Name: Adit Chaudhary  
- Registration Number: 24BCE10767  
- Course: Open Source Software  
- University: VIT Bhopal University  

---

## 🐍 Project Description

In this project, I selected **Python** as my open-source software. Python is a well-known programming language that focuses on simplicity and readability. It is widely used in different areas such as web development, automation, data science, and AI.

The purpose of this project was to understand how open-source software works and to get hands-on experience with Linux and shell scripting.

---

## 📂 What is Included

This repository contains:

- Five shell scripts (.sh files)  
- A project report (submitted on the portal)  
- This README file  

---

## 💻 About the Scripts

### Script 1 — System Identity Report
This script shows basic details about the system like the user name, kernel version, uptime, and date. It helps in understanding system information.

---

### Script 2 — FOSS Package Inspector
This script checks whether Python is installed on the system. It also displays some details about the package and prints a short description.

---

### Script 3 — Disk and Permission Auditor
This script checks important system folders and displays their size, permissions, and ownership details. It also verifies the Python directory.

---

### Script 4 — Log File Analyzer
This script reads a log file and counts how many times a keyword appears. It also shows the last few matching lines from the log.

---

### Script 5 — Open Source Manifesto Generator
This script asks the user a few questions and creates a short statement about open source. The output is saved in a file.

---

## ⚙️ Requirements

To run this project, you need:

- Linux (Ubuntu preferred)  
- Bash shell  
- Basic knowledge of terminal commands  

---

## ▶️ Steps to Run the Scripts

### 1. Open Terminal
Press:Ctrl + Alt + T

### 2. Go to the project folder

cd oss_project

### 3. Give permission to scripts

chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

### 4. Run the scripts

Run each script using:

./script1.sh
./script2.sh
./script3.sh

For Script 4:
./script4.sh /var/log/syslog error

If it does not work:
./script4.sh /var/log/auth.log error


For Script 5:

./script5.sh
## 📌 Important Points

- Some log files may need admin access:

sudo ./script4.sh /var/log/syslog error


- If you don’t get output, try a different keyword like:

./script4.sh /var/log/syslog warning


## 📊 What I Learned

While working on this project, I learned:

- Basics of open-source software  
- How Linux works internally  
- Writing and running shell scripts  
- Using terminal commands for simple automation  

Initially, I was not very comfortable with Linux, but after completing this project, I feel much more confident.


## 🔗 Submission

This repository is part of my OSS Capstone Project submission. It includes all required scripts, and the report has been submitted separately on the VITyarthi portal.
