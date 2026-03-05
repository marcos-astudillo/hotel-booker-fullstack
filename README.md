
# Hotel Booker – Fullstack App (Django + Angular)

![Django](https://img.shields.io/badge/Django-5.2-green?logo=django)
![Angular](https://img.shields.io/badge/Angular-17-red?logo=angular)
![Render](https://img.shields.io/badge/Frontend-Render-blue?logo=render)
![Railway](https://img.shields.io/badge/Backend-Railway-black?logo=railway)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?logo=jsonwebtokens)

A full-stack hotel reservation management system built with **Django REST API** and **Angular**.  
The application allows users to authenticate securely and manage hotel reservations with full CRUD functionality.

The project is deployed with:

- **Frontend:** Render
- **Backend API:** Railway
- **Database:** PostgreSQL (Railway)

---

## ✨ Features

- 🔐 JWT-based authentication
- 📋 Create, view, update, and delete reservations
- 📧 Reservation fields: guest name, email, phone, room number, check-in & check-out
- 🔎 Search reservations by name, room number, phone or email
- ⚙️ Protected routes using Angular guards
- 📱 Responsive Bootstrap UI
- 🌍 Full cloud deployment (Render + Railway)
- 🧪 Automatic database migrations during deploy
- 👤 Demo user automatically created during deployment

---

## 🔑 Demo Credentials

You can test the application using the following account:

```
username: demo
password: demo123
```

The demo user is automatically created during deployment if it does not exist.

---

## 🖼️ Screenshots

### ✅ Home & Reservation List

![Home screen](./screenshots/HomeScreen.png)

### ✏️ Editing a Reservation

![Editing](./screenshots/EditingaReservation.png)

### 🔐 Login Page

![Login](./screenshots/Login.png)

---

## ⚙️ Tech Stack

### Frontend

- Angular 17
- Bootstrap 5
- Angular Standalone Components
- Render Deployment

### Backend

- Django 5
- Django REST Framework
- JWT Authentication
- PostgreSQL
- Railway Deployment

---

## 🏗️ Architecture

Frontend (Angular)
⬇
REST API (Django + DRF)
⬇
PostgreSQL Database (Railway)

The backend handles authentication, business logic, and database operations while Angular provides a modern SPA interface.

---

## 🚀 Live Demo

🔗 Frontend:  
https://hotel-booker-fullstack.onrender.com/

🔗 Backend API:  
https://hotel-booker-backend-production.up.railway.app/api

---

## 💻 Local Setup

### Backend

```bash
cd api
python -m venv env
env\Scripts\activate   # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend

```bash
cd webapp
npm install
ng serve
```

Frontend will run on:

```
http://localhost:4200
```

Backend API will run on:

```
http://127.0.0.1:8000
```

---

## 🧠 Deployment Notes

- Database migrations run automatically during Railway deploy.
- Static files are collected automatically.
- A demo user is created if it does not already exist.
- Environment variables are managed through Railway service variables.

---

## 📫 Connect With Me

<p align="center">

  <a href="https://www.marcosastudillo.com">
    <img src="https://img.shields.io/badge/Website-marcosastudillo.com-blueviolet?style=for-the-badge&logo=google-chrome" />
  </a>

  <a href="https://www.linkedin.com/in/marcos-astudillo-c/">
    <img src="https://img.shields.io/badge/LinkedIn-Marcos%20Astudillo-blue?style=for-the-badge&logo=linkedin" />
  </a>

  <a href="https://github.com/marcos-astudillo">
    <img src="https://img.shields.io/badge/GitHub-Marcos%20Astudillo-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>

  <a href="mailto:m.astudillo1986@gmail.com">
    <img src="https://img.shields.io/badge/Email-m.astudillo1986%40gmail.com-red?style=for-the-badge&logo=gmail" />
  </a>

</p>
