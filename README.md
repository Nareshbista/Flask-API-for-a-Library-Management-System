# Flask-API-for-a-Library-Management-System
(a) How to run the project
# Library Management System API

This is a Flask-based API for managing books and members in a library. It supports CRUD operations for books and members.

## Features
- Manage Books: Add, view, update, and delete books.
- Manage Members: Add, view, update, and delete members.

## How to Run the Project

### Prerequisites
1. Python 3.8 or later.
2. `pip` for managing Python packages.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LibraryManagementSystem.git
   cd LibraryManagementSystem
    Run the Flask application:
      python app.py
   
   (b)Design Choices:
   
a.In-memory Storage: For simplicity and demonstration purposes, data is stored in Python lists. This can be replaced with a database like MySQL or MongoDB for production.
b.RESTful Design: Each resource (Books and Members) has its own set of CRUD operations.
c.Error Handling: Ensures proper HTTP status codes and error messages for invalid requests.

(c)Assumptions and Limitations:

1.Assumes unique IDs for books and members.
2.In-memory storage means data is lost on server restart.
3.Limited validation on input fields. Extend this in production environments
