# 💰 Finance Tracker API

A production-ready **FastAPI backend** for tracking personal income and expenses.  
Features **user authentication**, **JWT access & refresh tokens**, **role-based access**, and **financial reporting**.

---

## 🚀 Features

- User registration and login with **bcrypt-hashed passwords**
- JWT **access and refresh tokens**
- **Role-based access**: `user` vs `admin`
- Add **income** and **expenses**
- Generate **income statements** (total income, total expenses, net income)
- **SQLite + SQLAlchemy ORM** database
- **Environment-variable configuration** for secrets, tokens, DB URL
- Logging of auth events for audit purposes
- Fully tested with **curl commands**

---

## 🛠️ Tech Stack

- Python 3.11+
- FastAPI
- SQLite (SQLAlchemy ORM)
- Passlib (bcrypt)
- Python-JOSE (JWT)
- Pydantic
- Uvicorn

---

## 📂 Project Structure

