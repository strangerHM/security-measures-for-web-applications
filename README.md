# Security Measures for Web Application
Securing a Library Management System is essential to protect sensitive data such as user information, borrowing history, and inventory records.
Implementing user authentication, hashed passwords , and encrypted database storage helps prevent unauthorized access. Input validation is  also critical to defend against common vulnerabilities like SQL injection or cross-site scripting .By ensuring robust security measures, the system maintains data integrity and user trust. I secured this particular Library Managemnt System  by defending it againt these common vulnerabilitites.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
  
## Installation

1. Clone the repository
  https://github.com/qutubuddinkhan07/Library-Management-System-LMS-.git
2. Navigate into the folder
cd Library-Management-System-LMS-
3. Install dependencies
npm install
## Usage
Run the server and open `http://localhost:3000` in your browser to view the app..

## Features

- User authentication
- Secureed with hashed passwords.
- Enter email address in contact
- Password should 10 or 10+
- Admin login secured.
- Admin Login passoword: admin123
- Used XSS and SQL injection
- Used Winston to gain security log.
- Ued bcrypt to hash passwords.
- Applied 'express-rate-limit' to prevent brute attack forces.
- Properly configured CORS to prevent unauthorized access.
- Applied API keys to secure.
- Used CSP to  prevents script injection by restricting allowed sources for scripts, styles, fonts, and images.
- Used HSTS that enforces HTTPS connections to protect against protocol downgrade attacks.

  

