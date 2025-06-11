# Learning Log

Learning Log is a Django-based web application that allows users to track their learning progress by creating topics and entries.

## Features
- User authentication (registration, login, logout).
- Create, edit, and delete topics.
- Add entries to topics.
- View and manage entries.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Mac/Linux
   .venv\Scripts\activate     # On Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

1. Open the application in your browser at `http://127.0.0.1:8000/`.
2. Register a new account or log in.
3. Create topics and add entries to track your learning progress.

## Project Structure

- **learning_logs**: Contains the main application logic (models, views, templates).
- **users**: Handles user authentication and registration.
- **templates**: Contains HTML templates for the application.
- **db.sqlite3**: SQLite database file.

## Requirements

- Python 3.13+
- Django 5.1.5
- Bootstrap 4 (via `django-bootstrap4`)
- asgiref 3.8.1
- sqlparse 0.5.3


## License

This project is licensed under the MIT License.
