# Online Bookstore System

A full-stack online bookstore application built with Flask (Backend) and Django (Frontend).

## Project Structure

- `backend/`: Flask REST API
  - Handles book and order management
  - SQLite database
  - RESTful endpoints for CRUD operations

- `frontend/`: Django Web Application
  - User interface for the bookstore
  - Shopping cart functionality
  - Order management
  - Admin interface

## Technologies Used

- Backend:
  - Flask
  - SQLite
  - Python

- Frontend:
  - Django
  - Django Rest Framework
  - HTML/CSS
  - Bootstrap

## Setup Instructions

1. Clone the repository

2. Set up the backend:
```bash
cd backend
pip install -r requirements.txt
python app.py
```

3. Set up the frontend:
```bash
cd frontend/bookstore
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

4. Access the application:
- Frontend: http://localhost:8000
- Backend API: http://localhost:5000

## Features

- Book management (CRUD operations)
- Shopping cart functionality
- Order processing
- User authentication
- Admin dashboard
