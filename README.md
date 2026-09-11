# Flask Blog Web Application

A full-stack blog web application built using Python and Flask. The application allows users to register, log in, create and manage blog posts, update their profiles, and securely manage their accounts.

## Features

- User Registration and Login
- User Authentication
- Create, Update and Delete Blog Posts
- User Profile Management
- Profile Picture Support
- Password Reset Functionality
- User-Specific Posts
- Form Validation
- Secure Password Hashing
- Custom Error Pages
- SQLite Database Integration
- Responsive Web Interface

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- Flask-Bcrypt
- Flask-Login
- Flask-WTF
- SQLite
- HTML5
- CSS3
- Jinja2

## Project Structure

```text
Flask_vlog/
│
├── flaskblog/
│   ├── errors/
│   ├── static/
│   ├── templates/
│   ├── __init__.py
│   ├── forms.py
│   ├── models.py
│   └── routes.py
│
├── config.py
├── requirements.txt
├── run.py
└── .gitignore