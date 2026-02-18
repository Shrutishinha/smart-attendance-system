<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=500&color=2F81F7&center=true&vCenter=true&width=900&lines=FINGERPRINT+ATTENDANCE+MANAGEMENT+SYSTEM;BUILT+WITH+FLASK+AND+SQLITE;SECURE+WEB+ATTENDANCE+PLATFORM;DEVELOPED+BY+SHRUTI" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PYTHON-3.8+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/FLASK-WEB-green?style=for-the-badge&logo=flask" />
  <img src="https://img.shields.io/badge/SQLITE-DATABASE-orange?style=for-the-badge&logo=sqlite" />
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-success?style=for-the-badge" />
</p>

---

# FINGERPRINT ATTENDANCE MANAGEMENT SYSTEM

> A MODERN, SECURE, AND SCALABLE WEB-BASED ATTENDANCE SYSTEM USING PYTHON FLASK AND SQLITE.

---

## PROJECT OVERVIEW

THIS PROJECT PROVIDES A SMART DIGITAL PLATFORM FOR MANAGING STUDENT ATTENDANCE USING A SIMULATED FINGERPRINT AUTHENTICATION MECHANISM. IT HELPS REDUCE MANUAL ERRORS, IMPROVE DATA ACCURACY, AND GENERATE DETAILED REPORTS.

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
- CSV EXPORT SUPPORT  
- RESPONSIVE USER INTERFACE  
- SESSION MANAGEMENT  

---

## TECHNOLOGY STACK

| LAYER     | TECHNOLOGY |
|-----------|------------|
| BACKEND   | PYTHON + FLASK |
| FRONTEND  | HTML + CSS + JAVASCRIPT |
| DATABASE  | SQLITE3 |
| SERVER    | FLASK DEVELOPMENT SERVER |

---

## PROJECT STRUCTURE

<details>
<summary>CLICK TO EXPAND</summary>

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

### STEP 2: INSTALL DEPENDENCIES

pip install -r requirements.txt


---

### STEP 3: INITIALIZE DATABASE

python database_setup.py


---

### STEP 4: RUN APPLICATION

python app.py


---

### STEP 5: OPEN IN BROWSER

http://localhost:5000


---

## DEFAULT LOGIN CREDENTIALS

USERNAME: admin
PASSWORD: admin123


CHANGE BEFORE PRODUCTION.

---

## MODULE WORKFLOW

```mermaid
graph TD
    A[Login] --> B[Dashboard]
    B --> C[Student Management]
    B --> D[Attendance Module]
    B --> E[Reports]
    D --> F[Fingerprint Scan]
    F --> G[Mark Present]
SECURITY FEATURES
SESSION-BASED AUTHENTICATION

ROUTE PROTECTION

INPUT VALIDATION

PARAMETERIZED QUERIES

SQL INJECTION PREVENTION

PASSWORD ENCRYPTION

SCREENSHOTS
LOGIN	DASHBOARD	REPORTS
IMG	IMG	IMG
ADD REAL IMAGES IN /screenshots

FUTURE ROADMAP
REAL BIOMETRIC DEVICE SUPPORT

CLOUD DATABASE INTEGRATION

MOBILE APPLICATION

ROLE-BASED ACCESS CONTROL

REST API SUPPORT

FACE RECOGNITION SYSTEM

AI-BASED ATTENDANCE ANALYTICS

CONTRIBUTING
<details> <summary>HOW TO CONTRIBUTE</summary>
FORK THE REPOSITORY

CREATE A FEATURE BRANCH

COMMIT CHANGES

PUSH TO YOUR BRANCH

SUBMIT PULL REQUEST

</details>
LICENSE
THIS PROJECT IS LICENSED UNDER THE MIT LICENSE.

AUTHOR
SHRUTI
COMPUTER SCIENCE STUDENT

SKILLS:
PYTHON | FLASK | MACHINE LEARNING | WEB DEVELOPMENT
