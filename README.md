# ✅ Todo5 – Django Task Manager

A simple and clean **To-Do / Task Manager web application** built with **Python and Django**. Users can add tasks and track whether each one is completed or still pending.

This is **Capstone Project 4**, built as part of my **Full Stack Python Internship at [CodingBrains](https://codingbrains.in)**.

---

## 🔗 Quick Links

| | Link |
|---|---|
| 🌐 **Live Demo** | https://sandyreddy377.pythonanywhere.com/ |
| 💻 **GitHub Repo** | https://github.com/reddyramasandhya-droid/todo5 |
| 🖥️ **Local Server** | http://127.0.0.1:8004/ |

---

## 📌 About the Project

Todo5 is a CRUD-style Django application that helps manage daily tasks. Each task has a title and a completion status, stored in a database through Django's ORM. The goal of this project was to practice the full Django workflow: models, migrations, views, templates, URL routing, and deployment.

## ✨ Features

- ➕ Add new tasks
- 📋 View all tasks in a list
- ☑️ Mark tasks as completed / pending
- 🗄️ Data stored using Django ORM with SQLite
- 🔐 Django Admin panel for managing data
- ☁️ Deployed on PythonAnywhere

## 📸 Screenshots

| Home / Task List | Add Task |
|---|---|
| ![Home Page](<img width="1907" height="321" alt="Image" src="https://github.com/user-attachments/assets/43eab7e0-fb53-439e-a5f1-88eb84dbed7e" />
) | ![Add Task](<img width="1912" height="1067" alt="Image" src="https://github.com/user-attachments/assets/f3400af4-ee1d-4679-908c-13f415332f64" />) |

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3 |
| Framework | Django 5.2 |
| Database | SQLite3 |
| Frontend | HTML, CSS (Django Templates) |
| Hosting | PythonAnywhere |
| Version Control | Git & GitHub |

## 🗃️ Database Model

**Task**

| Field | Type | Description |
|---|---|---|
| `id` | AutoField | Primary key |
| `task` | CharField (max 200) | Task title |
| `is_completed` | BooleanField | Completion status |

## 📁 Project Structure

```
todo5/
├── app/                # Main Django app (models, views, templates)
├── todo/               # Project settings and root URL configuration
├── screenshots/        # Images used in this README
├── manage.py           # Django command-line utility
├── db.sqlite3          # SQLite database
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

## 🚀 Getting Started (Run Locally)

### 1. Clone the repository
```bash
git clone https://github.com/reddyramasandhya-droid/todo5.git
cd todo5
```

### 2. Create and activate a virtual environment
```bash
python -m venv env

# Windows
env\Scripts\activate

# macOS / Linux
source env/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply migrations
```bash
python manage.py migrate
```

### 5. (Optional) Create an admin user
```bash
python manage.py createsuperuser
```

### 6. Run the development server
```bash
python manage.py runserver 8004
```

Open **http://127.0.0.1:8004/** in your browser. 🎉

## ☁️ Deployment (PythonAnywhere)

1. Clone the project on PythonAnywhere from a Bash console (`git clone`).
2. Create a virtualenv and run `pip install -r requirements.txt`.
3. Create a new **Web app** (Manual configuration) and set the source code and virtualenv paths.
4. Edit the WSGI file so it points to `todo.settings`.
5. Add your domain to `ALLOWED_HOSTS` in `settings.py`.
6. Run `python manage.py migrate` and reload the web app.

## 📚 What I Learned

- Building a Django project and app from scratch
- Designing models and running migrations
- Writing views, templates, and URL routing
- Working with the Django ORM and Admin panel
- Using Git and GitHub for version control
- Deploying a Django app to a live server (PythonAnywhere)

## 🔮 Future Improvements

- Edit and delete tasks
- User authentication so each user sees only their own tasks
- Due dates, priorities, and categories
- Better UI with Bootstrap

## 👩‍💻 Author

**Somula Rama Sandhya**
BTech (AIML) – Presidency University, Bengaluru (2024–2028)
Full Stack Python Intern @ CodingBrains

GitHub: [@reddyramasandhya-droid](https://github.com/reddyramasandhya-droid)

---

⭐ If you found this project helpful, feel free to star the repo!
