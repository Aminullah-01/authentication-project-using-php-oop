Project Title: Authentication System using PHP OOP
Description:

This project is a secure user authentication system built using Object-Oriented PHP (OOP) and MySQL. It demonstrates modern programming principles, including separation of concerns, encapsulation, and reusable classes.

The system allows users to:

Register: Create an account with full name, username, email, and password. Passwords are securely hashed before storing in the database.
Login: Authenticate with username and password. Validates credentials and manages user sessions.
Logout: Safely destroy sessions to log out the user.
Password Reset: Request a password reset via email, generate secure tokens, validate tokens, and set a new password.
Key Features:
OOP Structure:
User class for representing user data
UserRepository class for database operations
AuthService class for authentication logic
PasswordResetService class for password reset functionality
Secure Practices:
Passwords are hashed using password_hash() and verified using password_verify().
Session regeneration on login to prevent session fixation attacks.
Generic messages for password reset requests to avoid email enumeration.
Database-Driven:
Uses PDO for secure database interactions with prepared statements.
Stores user data, hashed passwords, and password reset tokens with expiration.
Extensible:
Modular design makes it easy to integrate with larger applications or convert to frameworks like Laravel.
Technologies Used:
PHP (OOP)
MySQL
HTML & CSS
PDO for secure database operations
Use Cases:
Any web application that requires user authentication
Learning resource for OOP, sessions, and secure authentication in PHP
