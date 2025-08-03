### Flask Notes App

A lightweight web application for managing notes with tags, using Flask and PostgreSQL. You can easily create, edit, delete, and categorize notes.

-----

### 📦 Requirements

  * `flask`
  * `flask-wtf`
  * `flask-sqlalchemy`
  * `wtforms-sqlalchemy`
  * `psycopg2-binary`

All can be installed using the command:

```bash
pip install -r requirements.txt
```

-----

### 🔧 Key Libraries and Usage

  * **Flask** – A lightweight WSGI web framework, it's the core of the application.
  * **Flask-WTF** – Handles forms and CSRF (Cross-Site Request Forgery) protection, working with WTForms.
  * **Flask-SQLAlchemy** – An ORM (Object-Relational Mapper) that makes database management easy through Python classes.
  * **WTForms-SQLAlchemy** – Helps automatically create forms from SQLAlchemy models.
  * **psycopg2-binary** – The PostgreSQL adapter used to connect to the database from Python.

These libraries work together to enable the rapid development of secure web applications that connect to a database, using minimal boilerplate code.

-----

### ▶️ How to Run

Run the application with the command:

```bash
python noteapp.py
```

Then, open a browser and go to `http://127.0.0.1:5000`.

-----

If you need a version that supports Docker or configuration via Environment Variables, please let us know.
