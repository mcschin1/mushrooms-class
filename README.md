# Django Project Setup Guide

Quick steps to set up a Django project from scratch.

---

## Setup Instructions

1. **Create Project Directory**
```bash
mkdir my_project
cd my_project
Build Virtual Environment

bash
Copy
Edit
python -m venv env
# Activate on Windows
env\Scripts\activate
# Activate on Linux/Mac
source env/bin/activate
Create Django Project

bash
Copy
Edit
django-admin startproject mysite
cd mysite
Create Django App

bash
Copy
Edit
python manage.py startapp myapp
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Apply Migrations

bash
Copy
Edit
python manage.py migrate
Run Development Server

bash
Copy
Edit
python manage.py runserver
