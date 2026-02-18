<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=500&color=2F81F7&center=true&vCenter=true&width=800&lines=FINGERPRINT+ATTENDANCE+MANAGEMENT+SYSTEM;BUILT+WITH+FLASK+AND+SQLITE;SECURE+WEB+ATTENDANCE+PLATFORM;BY+SHRUTI" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PYTHON-3.8+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/FLASK-WEB-green?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/SQLITE-DATABASE-orange?style=for-the-badge&logo=sqlite" />
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-success?style=for-the-badge" />
</p>

---

# FINGERPRINT ATTENDANCE MANAGEMENT SYSTEM

> A MODERN, SECURE, AND SCALABLE WEB-BASED ATTENDANCE SYSTEM USING FLASK AND SQLITE.

---

<p align="center">
  <img src="https://user-images.githubusercontent.com/00000000/demo.gif" width="800"/>
</p>

---

## PROJECT OVERVIEW

THIS PROJECT PROVIDES A SMART DIGITAL PLATFORM FOR:

- AUTOMATING ATTENDANCE  
- REDUCING MANUAL WORK  
- GENERATING REAL-TIME REPORTS  
- ENSURING DATA SECURITY  

IT USES A FINGERPRINT SIMULATION SYSTEM WHICH CAN BE EXTENDED TO REAL BIOMETRIC DEVICES.

---

## SYSTEM CAPABILITIES

LOGIN SYSTEM ██████████████ 100%
STUDENT MANAGEMENT ██████████████ 100%
ATTENDANCE MODULE ████████████░░ 90%
REPORTING SYSTEM ███████████░░░ 85%
SECURITY FEATURES ████████████░░ 90%


---

## FEATURES

- SECURE ADMIN AUTHENTICATION  
- STUDENT AND CLASS MANAGEMENT  
- FINGERPRINT SIMULATION  
- REAL-TIME ATTENDANCE TRACKING  
- DETAILED REPORTS  
- CSV EXPORT  
- RESPONSIVE UI  
- SESSION MANAGEMENT  

---

## TECHNOLOGY STACK

| LAYER     | TECHNOLOGY |
|-----------|------------|
| BACKEND   | PYTHON + FLASK |
| FRONTEND  | HTML + CSS + JS |
| DATABASE  | SQLITE3 |
| SERVER    | FLASK DEV SERVER |

---

## PROJECT STRUCTURE

<details>
<summary>CLICK TO EXPAND STRUCTURE</summary>

attendance_app/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│ ├── base.html
│ ├── login.html
│ ├── dashboard.html
│ ├── students.html
│ ├── attendance.html
│ ├── reports.html
│ └── classes.html
│
├── static/
│ ├── css/style.css
│ └── js/script.js
│
└── README.md


</details>

---

## INSTALLATION GUIDE

### STEP 1: CLONE REPOSITORY

git clone https://github.com/your-username/fingerprint-attendance-system.git
cd fingerprint-attendance-system


---

### STEP 2: INSTALL PACKAGES

pip install -r requirements.txt


---

### STEP 3: INITIALIZE DATABASE

python database_setup.py


---

### STEP 4: RUN APPLICATION

python app.py


---

### STEP 5: OPEN BROWSER

http://localhost:5000


---

## LOGIN DETAILS

USERNAME: admin
PASSWORD: admin123


CHANGE IN PRODUCTION.

---

## MODULE WORKFLOW

```mermaid
graph TD
A[LOGIN] --> B[DASHBOARD]
B --> C[STUDENTS]
B --> D[ATTENDANCE]
B --> E[REPORTS]
D --> F[FINGERPRINT SCAN]
F --> G[MARK PRESENT]
SECURITY LAYER
SESSION AUTH

ROUTE PROTECTION

SQL INJECTION PREVENTION

INPUT SANITIZATION

PASSWORD HASHING

SCREENSHOTS
LOGIN	DASHBOARD	REPORT
IMG	IMG	IMG
ADD REAL IMAGES IN /screenshots

FUTURE ROADMAP
REAL BIOMETRIC DEVICE

CLOUD DEPLOYMENT

MOBILE APP

FACE AI

REST API

ADMIN ROLES

AI ANALYTICS

CONTRIBUTING
<details> <summary>HOW TO CONTRIBUTE</summary>
FORK PROJECT

CREATE BRANCH

COMMIT

PUSH

PULL REQUEST

</details>
LICENSE
MIT LICENSE

AUTHOR
SHRUTI
COMPUTER SCIENCE STUDENT

SPECIALIZATION:
PYTHON | FLASK | ML | WEB DEV
