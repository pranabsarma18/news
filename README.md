# 📰 News Web Application using Django

A full-stack **News Publishing Web Application** developed using Django.  
The application allows users to read and manage news articles through a clean, secure, and scalable backend system.  
It is deployed on Heroku with PostgreSQL as the production database.

🌐 **Live Website:**  
https://protected-coast-00893-5854a6906bdb.herokuapp.com/

📂 **GitHub Repository:**  
https://github.com/pranabsarma18/news

---

## 📖 Abstract

The **News Web Application** is a Django-based web platform designed to demonstrate real-world backend web development using Python.  
It provides features such as user authentication, article management, database integration, and cloud deployment.

The project follows Django’s **Model–View–Template (MVT)** architecture and uses environment-based configuration for production readiness.

---

## 🎯 Objectives

- Build a dynamic web application using Django  
- Implement secure user authentication and authorization  
- Perform CRUD operations on news articles  
- Integrate PostgreSQL as a production database  
- Deploy a Django application on a cloud platform  
- Gain hands-on experience with real-world debugging and deployment  

---

## 🛠️ Tech Stack

### Backend
- Django (Django 5.x)
- Python 3.12

### Database
- PostgreSQL

### Frontend
- HTML5  
- CSS3  
- Django Template Engine  

### Deployment & Tools
- Heroku
- Gunicorn (WSGI Server)
- WhiteNoise (Static file handling)
- Git & GitHub

---

## 🚀 Features

- 🔐 User Authentication (Login / Logout)
- 👤 Custom User Model
- 📰 Create, Read, Update & Delete (CRUD) News Articles
- 📦 PostgreSQL database integration
- 🎨 Responsive UI using Django templates
- ⚡ Static file serving with WhiteNoise
- ☁️ Cloud-based production deployment

---

## 🏗️ Project Architecture

The project follows Django’s standard project structure and is organized into multiple reusable applications to ensure modularity, scalability, and maintainability.

news/
│
├── accounts/        # Custom user model and authentication logic
├── articles/        # News article CRUD functionality
├── pages/           # Static and home pages
├── templates/       # Global HTML templates
├── static/          # CSS, JS, and static assets
│
├── django_project/
│   ├── settings.py  # Main project settings
│   ├── urls.py      # URL routing configuration
│   ├── wsgi.py      # WSGI entry point for deployment
│   └── asgi.py      # ASGI configuration
│
├── manage.py        # Django management script
├── Procfile         # Heroku process definition
├── runtime.txt      # Python runtime version
└── requirements.txt # Project dependencies

This structure separates concerns between authentication, content management, and static pages, making the application easy to extend and maintain.

---

## ⚙️ Django MVT Architecture

The application is built using Django’s **Model–View–Template (MVT)** architecture.

### Model
Defines the database schema and manages data operations using the Django ORM.

### View
Handles business logic and processes HTTP requests and responses.

### Template
Renders dynamic HTML pages for the user interface.

This architectural pattern improves code readability, reusability, and long-term maintainability.

---

## 🔐 Environment Variables

The following environment variables are required to run the application in a **production environment**:

```env
SECRET_KEY=your_secret_key
DEBUG=False
DATABASE_URL=postgres://...
```

---

## 🧪 Local Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/pranabsarma18/news.git
cd news
```

### Create and Activate Virtual Environment
```python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows
```

### Install Dependencies
```pip install -r requirements.txt```

### Apply Database Migrations
```python manage.py migrate
python manage.py runserver
```

### Run Development Server
```http://127.0.0.1:8000/```

### Open your browser and visit:
```http://127.0.0.1:8000/```

## 🌍 Deployment on Heroku

The application is deployed using:

- Gunicorn as the WSGI server
- PostgreSQL add-on database
- WhiteNoise for static file management
- Environment-based configuration

This setup ensures the application runs reliably and securely in a production environment.

---

## 📈 Learning Outcomes

- Understanding Django project structure and MVT architecture
- Implementing custom user authentication
- Using PostgreSQL with Django ORM
- Managing environment variables securely
- Deploying Django applications on Heroku
- Debugging production-level issues

---

## 🔮 Future Enhancements

- Add article categories and tags
- Implement comments and likes system
- Add search and filtering functionality
- Enable image uploads for articles
- Improve UI and responsiveness
- Add SEO and performance optimizations

---

## 👨‍💻 Author

**Pranab Sarma**

- GitHub: https://github.com/pranabsarma18  
- Live Project: https://protected-coast-00893-5854a6906bdb.herokuapp.com/

---

## ⭐ Acknowledgements

- Django Official Documentation
- Heroku Platform
- Open-source Django Community
