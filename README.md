## 📌 Project Overview

This project is a secure web-based application developed as part of an academic course.
The main objective of the project is to design and implement a **secure authentication
and authorization system** by following modern web security best practices.

The system allows users to register, login, and access the application securely.
Special emphasis has been given to protecting the system against common security threats
such as brute-force attacks, SQL injection, session hijacking, and unauthorized access.

This project is implemented using **PHP and MySQL**, and multiple security layers have
been added to ensure data protection, user privacy, and system reliability.


## 🔐 Security Features Implemented

The following security mechanisms have been implemented in this project:

1. **Google reCAPTCHA Integration**  
   Prevents automated bot attacks during authentication.  
   *Implemented by: Rakib*
2. **Strong Password Policy**  
   Enforces strong passwords using length and complexity rules.  
   *Implemented by: Jhorna*
3. **OTP for Every Login**  
   One-Time Password is required for each login attempt.  
   *Implemented by: Rakib*
4. **Email Verification via OTP**  
   User email is verified using OTP before account access.  
   *Implemented by: Rakib*
5. **Password Hashing**  
   User passwords are securely stored using hashing techniques.  
   *Implemented by: Tamim*
6. **Blacklisted IP Protection**  
   Blocks malicious IP addresses from accessing the system.  
   *Implemented by: Labiba*

7. **Session Auto Logout**  
   Automatically logs out users after inactivity.  
   *Implemented by: Labiba*
8. **CSRF Protection**  
   Prevents Cross-Site Request Forgery attacks.  
   *Implemented by: Labiba*
9. **Rate Limiting (Wrong Password Attempts)**  
   Limits repeated failed login attempts to prevent brute-force attacks.  
   *Implemented by: Labiba*
10. **SQL Injection Protection**  
    Protects database queries using prepared statements.  
    *Implemented by: Jhorna*
11. **JavaScript Injection Protection (Input Sanitization)**  
    Prevents XSS attacks by sanitizing user inputs.  
    *Implemented by: Tamim*
12. **Secure Session Termination**  
    Ensures proper destruction of sessions on logout.  
    *Implemented by: Tamim*
13. **Role-Based Authentication**  
    Provides different access levels based on user roles.  
    *Implemented by: Jhorna*
14. **Input Validation using Regular Expressions**  
    Validates user input formats to prevent malicious data submission.  
    *Implemented by: Rakib*

## 🛠️ Technologies Used

The project is developed using the following technologies and tools:

- **PHP (Core PHP)**  
  Used for server-side logic, authentication, OTP handling, and security implementation.
- **MySQL**  
  Used as the relational database to store user data, OTP records, sessions, and logs.
- **HTML5 & CSS3**  
  Used for structuring and styling the user interface.
- **JavaScript**  
  Used for client-side validation and improving user interaction.
- **PHPMailer**  
  Used to send OTP emails securely to users.
- **Google reCAPTCHA**  
  Integrated to protect the system from automated bot attacks.
- **Apache Server (XAMPP)**  
  Used as the local development server environment.

## 🗄️ Database Setup

Follow the steps below to set up the database for this project:

1. Open **phpMyAdmin** from XAMPP control panel.
2. Create a new database named: **farmsystem**
3. Navigate to the **Import** tab.
4. Import the SQL file located at: **database/farmsystem.sql**
   
This will automatically create all required tables such as user information, OTP storage,
and other related data used for authentication and security.

## 🚀 How to Run the Project

To run this project on your local machine, follow the steps below:

1. Install **XAMPP** on your system.
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Copy the project folder and paste it into: **C:\xampp\htdocs\**
4. Open a web browser and go to: **http://localhost/CS-project/**
5. Make sure the database is properly imported before using the application.
   The application is now ready to use on localhost

   “We used PHP and MySQL with XAMPP, imported the database using phpMyAdmin, and ran the project through localhost.”



