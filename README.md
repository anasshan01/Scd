# FastAPI Task Management Application

paste app file in scdlabbprojjanas folder and then run project

This is a simple task management web application built using FastAPI. It allows users to register, log in, view their tasks, and perform CRUD (Create, Read, Update, Delete) operations on their tasks. The application uses HTML templates rendered by Jinja2 for the frontend and stores user data and tasks in a database.

## Features

- **User Registration**: Users can register with a username and password.
- **User Login**: Registered users can log in to access their tasks.
- **Task Management**: Users can add, edit, and delete tasks.
- **Responsive Design**: The HTML pages are designed to be responsive and aesthetic, ensuring a good user experience across devices.
- **Secure**: Passwords are securely hashed before storing them in the database.


## Project Structure

scdlabbprojj2anas/ ├── app/ │ ├── init.py │ ├── main.py # Main FastAPI app │ ├── models.py # Database models │ ├── routes/ │ │ ├── init.py │ │ ├── auth.py # Authentication routes │ │ ├── tasks.py # Task management routes │ ├── templates/ │ │ ├── login.html # Login page │ │ ├── dashboard.html # Dashboard page │ ├── static/ │ │ ├── css/ │ │ │ └── styles.css # Custom CSS ├── .venv/ # Virtual environment ├── requirements.txt # Project dependencies └── README.md # Project documentation

Technologies Used
FastAPI

Jinja2

SQLite

UVicorn


This file provides a complete overview of your FastAPI Task Management application with installation instructions, project structure, and technologies used.
