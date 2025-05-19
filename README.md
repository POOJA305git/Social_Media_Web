# 📸 Instagram Clone (Django)

This is a full-featured Instagram-like web application built with **Django**. Users can sign up, log in, send and accept friend requests, create and manage posts, like, comment, share posts, and update their profiles.

---

## 🚀 Features

- 🔐 User Authentication (Login / Signup)
- 👥 Friend Requests (Send & Accept)
- 📝 Create, Edit, Delete Posts
- ❤️ Like & Comment on Posts
- 🔄 Share Posts
- 👤 User Profile Update
- 📸 Media Upload Support
- 📬 Notifications (optional/future)
- 🧾 REST API (if applicable)

---

## 🛠️ Tech Stack

- **Backend**: Django 4.x
- **Database**: SQLite (default) / PostgreSQL / MySQL
- **Frontend**: HTML, CSS, JavaScript (or Bootstrap/Tailwind if used)
- **Authentication**: Django Auth
- **File Storage**: Django Media Storage
- **Deployment**: Heroku / Railway / PythonAnywhere / Render

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/django-instagram-clone.git
cd django-instagram-clone
2. Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt
4. Apply Migrations & Create Superuser
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
5.Run the Development Server
python manage.py runserver


