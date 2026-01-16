# Emp-mg (Employee Management Application)

Grayson Leaphart – Application Development 1,2 – Newberry College

# Overview

(All code for this Project is in the master branch of this Github Repository)

Emp-mg is a web-based employee management application built with Django. It provides a centralized system for managing employee data and tasks within an organization. The application emphasizes simplicity and ease of use, allowing users to create accounts, log employees, assign tasks, and update information efficiently.

# Project Structure

emp-mg/
│
├── Empmg/                   # Django application
│   ├── migrations/          
│   ├── templates/           # HTML templates
│   │   ├── createaccount.html
│   │   ├── createemp.html
│   │   ├── createnote.html
│   │   ├── home.html
│   │   ├── signin.html
│   │   ├── update.html
│   │   └── userhome.html
│   ├── static/              # CSS and images
│   │   ├── css/
│   │   ├── js/
│   │   └── img/
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── web_project/             # Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py                # Django management script
├── db.sqlite3               # SQLite database (auto-generated)
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

# Technology Stack

Backend: Python 3.10+, Django 5.0

Database: SQLite

Frontend: HTML, CSS, JavaScript

Version Control: Git / GitHub

The project runs locally without external dependencies beyond a modern web browser.

# How to Run

Follow these steps to run the Emp-mg application locally:

1. Clone the repository

git clone https://github.com/GrayLeaphart/emp-mg.git
cd emp-mg

2. Create a Python virtual environment

python -m venv venv

3. Activate the virtual environment

source venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

5. Run database migrations

python manage.py migrate

6. Run Django development server

python manage.py runserver
http://127.0.0.1:8000/

7. Explore the Application

Navigate to the home page to sign in or create a new account.

Once logged in, access the user dashboard to:

Add new employees

Update or delete existing employees

Create or remove tasks

The dashboard is interactive and responsive, providing a ready-to-use demo environment for potential employers.

# Notes - 

Python 3.10+ is required

No manual database setup is needed; SQLite is automatically managed by Django

CSS and JavaScript are pre-configured for a modern UI
