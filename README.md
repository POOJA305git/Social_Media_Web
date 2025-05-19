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



---

## 🛠️ Tech Stack

- **Backend**: Django 4.x
- **Database**: SQLite (default) 
- **Frontend**: HTML, CSS, JavaScript 
- **File Storage**: Django Media Storage


---

## ⚙️ Setup Instructions

Follow these steps to run the project locally:

### 🔧 1–6: Setup & Run

```bash
# 1. Clone the Repository
git clone https://github.com/yourusername/django-instagram-clone.git
cd django-instagram-clone

# 2. Create & Activate Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install Dependencies
pip install -r requirements.txt

# 4. Apply Migrations
python manage.py makemigrations
python manage.py migrate

# 5. Create Superuser
python manage.py createsuperuser

# 6. Run the Development Server
python manage.py runserver
