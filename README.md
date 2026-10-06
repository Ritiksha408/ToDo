# ToDo
# Django Todo App

A simple and beginner-friendly **Todo List web application** built with **Python and Django**.

This project allows users to create and manage tasks through a clean web interface. It was built while learning the fundamentals of Django, including apps, views, URLs, templates, models, and database operations.

##  Features

* Add new tasks
* View all tasks
* Mark tasks as completed
* Delete tasks
* Display the number of tasks
* Custom HTML/CSS interface
* Django database integration

##  Tech Stack

* **Python**
* **Django**
* **HTML5**
* **CSS3**
* **SQLite**

## Project Structure

```text
django-project/
│
├── manage.py
│
├── todo/
│   ├── migrations/
│   ├── templates/
│   │   └── todo/
│   │       └── list.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── ...
│
├── todoproject/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── static/
│   ├── css/
│   └── image/
│
├── db.sqlite3
└── requirements.txt
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd django-project
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```powershell
venv\Scripts\Activate.ps1
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

## What I Learned

Through this project, I practiced:

* Understanding Django project and app structure
* Creating Django applications
* Working with `views.py`
* Configuring URL routing
* Creating and rendering Django templates
* Using Django template syntax
* Working with models and databases
* Handling static files
* Using migrations
* Running a Django development server
* Connecting frontend templates with backend logic
