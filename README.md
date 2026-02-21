# 📝 Django To-Do List App

A simple and clean To-Do List web application built with Django.  
Users can add tasks, mark them as completed, and track daily progress with a progress bar.

🔗 **Live Demo:**  
https://to-do-list-wfmp.onrender.com

---

## 🚀 Features

- Add new tasks
- Mark tasks as completed
- Daily task tracking
- Dynamic progress bar (based on completed tasks)
- Django Admin Panel
- PostgreSQL database (Production Ready)
- Deployed on Render

---

## 🛠️ Tech Stack

- Python
- Django
- HTML / CSS
- PostgreSQL
- Gunicorn
- Whitenoise
- Render (Deployment)

---

## 📊 How Progress is Calculated

The daily progress bar is calculated using:

```
(Completed Tasks / Total Tasks) × 100
```

Example:
If 3 out of 5 tasks are completed → Progress = 60%

---

## ⚙️ Installation (Run Locally)

Clone the repository:

```
git clone https://github.com/yourusername/your-repo-name.git
```

Navigate into the project:

```
cd your-repo-name
```

Create virtual environment:

```
python -m venv venv
```

Activate environment:

Windows:
```
venv\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

Run migrations:

```
python manage.py migrate
```

Start server:

```
python manage.py runserver
```

Open in browser:
```
http://127.0.0.1:8000/
```

---

## 📂 Project Structure

```
todo_project/
│── manage.py
│── todo_app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│── templates/
│── static/
│── requirements.txt
│── Procfile
```

---

## 🔐 Admin Access

Admin Panel:
```
https://to-do-list-wfmp.onrender.com/admin/
```

---

## 🌟 Future Improvements

- User Authentication
- Task Categories
- Due Date Reminders
- Dark Mode
- REST API version

---

## 👩‍💻 Author

Built with ❤️ using Django  
GitHub: https://github.com/Ruchika402

---

## ⭐ If you like this project

Give it a star on GitHub ⭐