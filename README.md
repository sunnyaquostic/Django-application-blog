# Django Blog Application

A simple blog platform built with Django, featuring user registration, authentication, profile management, and post creation.

---

## 🚀 Features

- User Registration and Login
- Logout with redirect
- Profile View and Edit
- Create, Update, and Delete Blog Posts
- Fully Responsive Frontend (Bootstrap)
- Django Messages Framework for Notifications
- Post Author Restrictions (Only post authors can edit/delete)
- Clean and Extendable Codebase

---

## 🛠 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default for development)
- **Others:** Django Forms, Django Auth, Django Messages

---

## 📁 Project Structure

myproject/
│
├── blog/ # Blog app (Post model, views, templates)
├── users/ # Custom user management (registration, profile)
├── templates/ # Global templates (base.html, login, logout)
├── media/ # User-uploaded content (profile images)
├── static/ # Static files (CSS, JS, etc.)
├── db.sqlite3 # Default SQLite database
├── manage.py
└── myproject/ # Settings and URLs

yaml
Copy
Edit

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/sunnyaquostic/django-blog-app.git
cd django-blog-app
Create and activate a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run migrations

bash
Copy
Edit
python manage.py migrate
Create a superuser (admin)

bash
Copy
Edit
python manage.py createsuperuser
Run the development server

bash
Copy
Edit
python manage.py runserver
Access the app
Visit http://127.0.0.1:8000/ in your browser.

🧪 Testing
You can run the test suite with:

bash
Copy
Edit
python manage.py test
🖼 Screenshots (Optional)
Add screenshots of the home page, login/register, post detail, and profile.

📌 Future Improvements
Comment system

Like/Dislike functionality

Pagination for posts

REST API using Django REST Framework

Search and filtering

📄 License
This project is open-source and available under the MIT License.

🙋‍♂️ Author
Your Name
📧 [sundayige.infotech@gmail.com]

💡 Acknowledgements
Django Documentation

Bootstrap

yaml
Copy
Edit

---

Would you like me to generate a `requirements.txt` file as well for the app?


WORK IN PROGRESS!!!