#Fingerprint Attendance Management System (Flask)

A web-based fingerprint attendance management system built using Python Flask and SQLite. This application allows administrators to manage students, mark attendance, and generate reports through a secure and user-friendly web interface.

Features

Secure admin login system

Student management (Add, Edit, Delete, View)

Class management

Attendance marking (Fingerprint simulation)

Attendance reports and statistics

SQLite database integration

Responsive web interface

Session-based authentication

CSV export support (optional)

Technologies Used

Backend: Python (Flask)

Frontend: HTML5, CSS3, JavaScript

Database: SQLite3

Server: Flask Development Server

Project Structure
attendance_app/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── dashboard.html
│   ├── students.html
│   ├── attendance.html
│   ├── reports.html
│   └── classes.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
└── README.md

Installation and Setup

Follow the steps below to run the project locally.

1. Prerequisites

Python 3.8 or higher

pip (Python package manager)

Web browser (Chrome, Edge, Firefox)

2. Clone the Repository
git clone https://github.com/your-username/fingerprint-attendance-system.git
cd fingerprint-attendance-system

3. Install Dependencies
pip install flask


(Optional)

pip install -r requirements.txt

4. Initialize Database

If database.db is not present, create it using the provided setup script or run:

python database_setup.py


(If included in the project)

5. Run the Application
python app.py

6. Open in Browser

Open your browser and navigate to:

http://localhost:5000

Default Login Credentials
Username: admin
Password: admin123


Note: It is recommended to change default credentials in production.

Usage
Admin Dashboard

View system statistics

Navigate to student and class management

Access attendance and reports

Student Management

Add new students

Edit existing records

Delete students

View all students

Attendance

Simulate fingerprint scan using roll number

Mark attendance

Prevent duplicate entries

Reports

View daily and monthly reports

Export attendance data

Analyze attendance trends

Fingerprint Integration

This project currently uses a fingerprint simulation mode. It can be extended to work with real biometric hardware by integrating compatible SDKs and APIs.

Security Features

Session-based authentication

Input validation

Protected routes

SQL injection prevention using parameterized queries

Screenshots

Add project screenshots here for better presentation.

Example:

/screenshots/login.png
/screenshots/dashboard.png

Future Enhancements

Real fingerprint sensor integration

Cloud database support

Mobile application support

Role-based user management

API-based attendance system

Face recognition support

Contributing

Contributions are welcome.

Steps:

Fork the repository

Create a new branch

Commit your changes

Push to your branch

Create a Pull Request

License

This project is licensed under the MIT License.

Author

Shruti

Computer Science Student
Python | Flask | Machine Learning | Web Development

Acknowledgements

Flask Documentation

SQLite Documentation

Open Source Community

If you want, I can also help you write:

requirements.txt

database_setup.py

Deployment guide

Resume description

Project presentation PPT
