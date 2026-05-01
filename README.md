# 🚀 Team Task Manager (Full-Stack | Flask)

A full-stack web application that enables users to create projects, assign tasks, and track progress with **role-based access control (Admin / Member)**.

🔗 **Live Demo:**
👉 https://team-task-manager-production-af20.up.railway.app/

---

## 📌 Assignment Objective

Build a web app where:

* Users can create projects
* Assign and manage tasks
* Track progress through a dashboard
* Enforce role-based access (Admin / Member)

---

## 🚀 Key Features

### 🔐 Authentication

* User Signup & Login
* Secure password hashing

### 👥 Role-Based Access Control

* **Admin**

  * Create projects
  * Assign tasks
  * Manage tasks
* **Member**

  * View assigned tasks
  * Update task status

### 📁 Project Management

* Create and manage projects
* Link tasks to specific projects

### 📝 Task Management

* Create tasks with:

  * Title
  * Description
  * Deadline
* Assign tasks to users
* Track task status:

  * Pending
  * In Progress
  * Completed

### 📊 Dashboard

* Total tasks
* Completed tasks
* Pending tasks
* Overdue tasks

---

## ⚙️ Requirements Covered

✔ REST APIs implemented (basic endpoints)
✔ Database integration (SQLite + SQLAlchemy)
✔ Proper relationships:

* User ↔ Task
* Project ↔ Task

✔ Role-based access control
✔ Input validation (basic form validation)

---

## 🔌 REST API Endpoints

| Method | Endpoint      | Description      |
| ------ | ------------- | ---------------- |
| GET    | /api/tasks    | Get all tasks    |
| POST   | /api/tasks    | Create new task  |
| GET    | /api/projects | Get all projects |

---

## ⚙️ Tech Stack

| Layer      | Technology           |
| ---------- | -------------------- |
| Backend    | Flask (Python)       |
| Database   | SQLite               |
| ORM        | SQLAlchemy           |
| Frontend   | HTML, CSS, Bootstrap |
| Auth       | Flask-Login          |
| Deployment | Railway              |

---

## 🚀 Local Setup

```bash
# Create virtual environment
python -m venv venv

# Activate
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py
```

Open:
👉 http://127.0.0.1:5000

---

## 🌐 Deployment

This application is deployed using Railway.

Steps:

1. Push code to GitHub
2. Deploy using Railway
3. Add:

   * requirements.txt
   * Procfile
4. App runs live

---

## 👤 Role Permissions

| Role   | Permissions                   |
| ------ | ----------------------------- |
| Admin  | Create projects, assign tasks |
| Member | Update task status            |

---

## 📈 Conclusion

This project successfully fulfills the assignment requirements by implementing:

* Authentication system
* Project and task management
* Role-based access control
* Dashboard for tracking progress
* REST APIs
* Live deployment

---

## 👩‍💻 Author

Kavya Jain
B.Tech CSE
