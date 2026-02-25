🩸 LifeLink – Blood Donation Management System
Project Overview
       LifeLink is a full-stack web application developed using Java Servlets, JSP, JDBC, and MySQL that connects blood donors and patients in real-time.
The system allows patients to search donors by blood group and location, send blood requests, and track request status. Donors can manage availability, accept or reject requests, and securely manage their accounts.
This project follows MVC architecture and implements secure authentication mechanisms using SHA-512 password hashing.

Key Features

👤 Patient Module
Patient Registration & Login
SHA-512 Password Encryption
Forgot Password Functionality
Search Donors by Blood Group & Location
Send Blood Request
View Request Status (Pending / Accepted / Rejected)
Soft Delete of Requests
Session-Based Secure Login

🧑‍⚕️ Donor Module
Donor Registration & Login
SHA-512 Password Encryption
Forgot Password Functionality
Toggle Availability Status
View Incoming Requests
Accept / Reject Requests
Soft Delete Own Requests
Real-time Pending Request Counter

🔐 Security Features
SHA-512 Password Hashing
Session Invalidation on Logout
Duplicate Request Prevention
Soft Delete Implementation
Role-Based Access Control

🏗 Architecture
The application follows MVC Architecture:
Model → Java Beans (Donor, Patient, BloodRequest)
View → JSP Pages
Controller → Servlets
DAO Layer → Database interaction using JDBC
Database → MySQL


🛠 Technology Stack
Java (JDK 21)
Servlets & JSP
JDBC
MySQL
Apache Tomcat 9
Maven
Git & GitHub
HTML5 & CSS3


🗄 Database Design
Tables:
donors
patients
blood_requests
admin

Implements:Foreign Key Relationships
Timestamp tracking
Soft delete logic
Status management


📊 Business Logic Highlights
Prevent duplicate blood requests to same donor
Only donor can update status of assigned requests
Only patient can delete their own request
Availability toggle controls donor visibility
Session-based authentication handling


🔮 Future Enhancements
Email Notification System
OTP-based Password Reset
Admin Dashboard Analytics
REST API Version
Spring Boot Migration
Deployment on Cloud


🎯 Learning Outcomes
Through this project, I gained hands-on experience in:
Secure Authentication Implementation
MVC Design Pattern
JDBC Database Integration
Session Management
Password Hashing using SHA-512
Handling Real-world Business Logic
Version Control using Git


👨‍💻 Developed By
Kammila Sudheer
B.Tech Final Year
Aspiring Java Full Stack Developer
