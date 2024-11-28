# Flask JWT RBAC: Authentication and Authorization System
# Overview
This project is an implementation of Authentication, Authorization, and Role-Based Access Control (RBAC) using Flask, JWT, and Poetry. The system ensures secure user authentication and authorization, allowing access to resources based on assigned roles.

The project is designed to demonstrate best practices in secure authentication mechanisms, RBAC integration, and clean code organization.

# Features
User Authentication:

Secure user registration and login.
Password hashing using industry-standard methods.
JWT-based token generation for session management.
Authorization:

Role-based access to endpoints and resources.
Multiple roles supported (e.g., Admin, Moderator, User).
Permissions tailored to roles.
Role-Based Access Control (RBAC):

Flexible RBAC implementation to define and manage roles and permissions.
Middleware to enforce role-based access to protected routes.
Security Best Practices:

Passwords hashed using cryptography.
JWT implementation for secure token-based authentication.
Environment variables used for sensitive data (e.g., JWT secret key).
Scalable and Modular Code:

Modular structure for easy scaling.
Fully documented and organized code.
# Technologies Used
Backend Framework: Flask
Authentication: JSON Web Tokens (JWT)
Role-Based Access Control: Custom RBAC implementation
Database: Flask-SQLAlchemy 
Environment Management: Python-dotenv
Package Management: Poetry
Cross-Origin Resource Sharing: Flask-CORS
HTTP Requests: Requests library
