# Credit Card Approval System

## Overview

The Credit Card Approval System is a web-based application developed to automate the process of credit card application submission, verification, and approval. The system enables users to apply for credit cards online while allowing administrators to evaluate applications based on predefined eligibility criteria such as income, credit score, employment status, and existing liabilities.

The application reduces manual processing time, improves decision-making, and provides a secure platform for managing customer information and application records.

---

# Objectives

- Automate the credit card application process.
- Reduce manual verification efforts.
- Improve approval accuracy using eligibility rules.
- Provide secure authentication for users and administrators.
- Maintain application history and approval records.
- Enable users to track their application status.

---

# Problem Statement

Traditional credit card approval processes involve manual verification of customer details, making them time-consuming and prone to errors. Banks receive numerous applications daily, making it difficult to process each application efficiently.

The Credit Card Approval System addresses this problem by providing an automated platform that evaluates applicant information based on predefined eligibility criteria and assists administrators in making faster and more accurate decisions.

---

# Features

## User Module

- User Registration
- Secure Login
- Apply for Credit Card
- Upload Required Documents
- View Application Status
- Update Personal Information

## Admin Module

- Admin Login
- View All Applications
- Search Applications
- Verify Applicant Details
- Approve or Reject Applications
- View Dashboard Statistics
- Generate Reports

---

# Eligibility Criteria

The system evaluates applicants based on:

- Age
- Annual Income
- Employment Type
- Credit Score
- Existing Loans
- Monthly Expenses
- Debt-to-Income Ratio
- Previous Loan Defaults

---

# Technology Stack

## Frontend

- HTML
- CSS
- JavaScript
- Bootstrap

## Backend

- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA

## Database

- MySQL

## Tools

- IntelliJ IDEA / Eclipse
- MySQL Workbench
- Postman
- Git
- GitHub
- Maven

---

# System Modules

## Authentication Module

- User Registration
- Login
- JWT Authentication
- Role-Based Authorization

## Application Management Module

- Submit Credit Card Application
- Edit Application
- Upload Documents
- Track Status

## Eligibility Evaluation Module

- Calculate Eligibility Score
- Validate Financial Information
- Generate Recommendation

## Admin Management Module

- Review Applications
- Verify Documents
- Approve/Reject Applications
- Generate Reports

---

# Database Tables

### Users

- User ID
- Name
- Email
- Password
- Phone Number
- Role

### Applicants

- Applicant ID
- User ID
- Age
- Occupation
- Salary
- Employment Type
- Address

### Credit Applications

- Application ID
- Applicant ID
- Card Type
- Applied Date
- Status
- Eligibility Score

### Credit History

- Credit Score
- Existing Loans
- Loan Defaults
- Monthly EMI

### Documents

- Aadhaar
- PAN Card
- Salary Slip
- Bank Statement

### Decisions

- Decision ID
- Application ID
- Approved By
- Decision
- Remarks

---

# Workflow

1. User registers an account.
2. User logs into the system.
3. User fills out the credit card application form.
4. User uploads required documents.
5. The system validates applicant information.
6. Eligibility score is calculated.
7. Application is submitted.
8. Administrator reviews the application.
9. Application is approved or rejected.
10. User receives the application status.

---

# Security Features

- JWT Authentication
- Password Encryption
- Role-Based Access Control
- Secure REST APIs
- Input Validation
- Exception Handling

---

# Future Enhancements

- Machine Learning-based approval prediction
- Email and SMS notifications
- PDF report generation
- Credit score API integration
- OTP verification
- Dashboard analytics using charts
- Cloud deployment
- Multi-bank support

---

# Advantages

- Faster approval process
- Reduced manual work
- Improved accuracy
- Secure user authentication
- Better record management
- Easy application tracking
- Scalable architecture

---

# Conclusion

The Credit Card Approval System simplifies and automates the credit card approval process by providing a secure, efficient, and user-friendly platform. It minimizes manual intervention, improves decision-making through automated eligibility evaluation, and enhances transparency for both applicants and administrators. The project demonstrates the practical implementation of Spring Boot, Spring Security, JWT Authentication, REST APIs, and MySQL in developing a real-world banking application.

---

# Developed Using

- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap
- Maven
- Git & GitHub
