https://img/logo/nbn.jpg

-A web-based application for managing student attendance records with role-based access for administrators and teachers.

-Features
Multi-Role Authentication

Administrators: Full system control

Class Teachers: Manage attendance for assigned classes

Secure Login System

Password hashing (MD5)

Session management

Attendance Management

Class-specific tracking

Teacher dashboards

Password Recovery

Forgot password functionality (in development)

Installation
Requirements
Web server (Apache/Nginx)

PHP 7.0+

MySQL 5.6+


Usage
Login Credentials
Administrator:
Username: admin@school.edu
Password: admin123

Class Teacher:
Username: teacher@school.edu
Password: teacher123

Screenshots
https://screenshots/login.png
Main login page with role selection

https://screenshots/admin-dashboard.png
Administrator dashboard

File Structure
text
student-attendance-system  
├── Admin/                # Admin dashboard files  
├── ClassTeacher/         # Teacher dashboard files  
├── Includes/  
│   └── dbcon.php           # Database connection  
├── img/                  # Images and logos  
├── vendor/               # CSS/JS libraries  
├── index.php             # Main login portal  
├── classTeacherLogin.php # Teacher login page  
├── forgotPassword.php    # Password recovery  
└── README.md             # This file  
