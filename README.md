# Library Management System

## Description

This is a Library Management System built with **Flask** and **MySQL** that allows both users and administrators to log in, borrow books, view borrowing history, and approve/deny borrowing requests.

### Key Features:
- **User Login**: Users can log in using their email and password.
- **Admin Login**: Admin can log in and manage book borrowing requests.
- **Book Borrowing**: Users can borrow books by specifying the dates they want to borrow the book.
- **Borrowing History**: Users can view their borrowing history, and admins can manage and approve/deny borrow requests.
- **CSV Export**: Users can download their borrowing history as a CSV file.

## Directory Structure

**library-management/**
├── app.py              # Main application file
├── templates/          # HTML files for rendering
│   ├── index.html      # Home page
│   ├── user_login.html # User login page
│   ├── admin_login.html# Admin login page
│   ├── user_dashboard.html # User dashboard
│   └── admin_dashboard.html # Admin dashboard
└── requirements.txt    # List of Python dependencies
