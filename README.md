# 📝 Flask Blog Project

A full-featured blog web application built with Flask and SQLAlchemy. 
Includes user authentication, rich text editing, comment functionality,
and admin-only access for post management.

---

## 🔧 Tech Stack

- Python
- Flask
- SQLAlchemy (SQLite)
- Flask-Bootstrap
- Flask-Login
- Flask-CKEditor
- Gravatar
- WTForms

---

## 💡 Features

- 🔐 User Registration & Secure Login (with hashed passwords)
- 📝 Create, Edit, and Delete Blog Posts (admin only)
- 💬 Add and view comments on posts
- 📸 User avatars via Gravatar
- 🖋 Rich text blog editor (CKEditor)
- 🎨 Responsive frontend using Flask-Bootstrap
- 🗄 Data stored in SQLite using SQLAlchemy ORM

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/OIdebi/blog-project.git
cd blog-project
```

Install dependencies
It's recommended to use a virtual environment.

```bash
pip install -r requirements.txt
```

If you don’t have a requirements.txt, create one by running:
```bash
pip freeze > requirements.txt
```

3. Run the app
```bash
python main.py
```
Go to http://127.0.0.1:5000/ in your browser.

🔐 Admin Access
To access post management (create/edit/delete), login as the admin user.
By default, the first registered user becomes the admin.
