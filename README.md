# Todo App

## Overview

This is a simple Todo App built with Django. It includes essential CRUD (Create, Read, Update, Delete) operations and user authentication features such as login, logout, and registration.

## Features

- User authentication (Signup, Login, Logout)
- Create, update, and delete tasks
- Mark tasks as completed
- View all tasks with status
- Secure and user-friendly interface

## Technologies Used

- Django
- HTML, CSS (for basic UI)
- SQLite (default Django database, can be changed)

## Installation & Setup

### 1. Clone the Repository

```sh
https://github.com/Nsushant1/Todo_App.git
```

### 2. Navigate to the Project Directory

```sh
cd Todo_App
```

### 3. Create a Virtual Environment

```sh
python -m venv venv
```

Activate it:

- **Windows:** `venv\Scripts\activate`
- **Linux/Mac:** `source venv/bin/activate`

### 4. Install Dependencies

```sh
pip install -r requirements.txt
```

### 5. Apply Migrations

```sh
python manage.py migrate
```

### 6. Create a Superuser (Admin Panel Access)

```sh
python manage.py createsuperuser
```

Follow the prompts to create an admin user.

### 7. Run the Development Server

```sh
python manage.py runserver
```

Access the application at `http://127.0.0.1:8000/`.

## Usage

- Register or log in to access the app.
- Add new tasks.
- Edit or delete tasks as needed.
- Mark tasks as completed.
- Logout when done.

## Future Improvements

- Add task deadlines & reminders
- Improve UI with Bootstrap&#x20;
- Implement API for task management

## License

This project is open-source and free to use.

