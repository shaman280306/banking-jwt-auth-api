# 💳 JWT Banking Authentication API

A secure and scalable backend system for banking applications using **JWT (JSON Web Tokens)** for authentication and authorization.

---

## 🚀 Project Overview

This project demonstrates industry-level security practices including:

- 🔐 JWT-based Authentication
- 🔑 Password Hashing using bcrypt
- 🛡️ Protected API Routes
- ⏳ Token Expiry Handling
- 🧩 Modular MVC Architecture
- 🌐 MongoDB Database Integration

---

## 🏗️ Architecture

The project follows a clean **MVC pattern**:

- **Models** → Database schema (User)
- **Controllers** → Business logic
- **Routes** → API endpoints
- **Middleware** → Authentication & security
- **Config** → Database connection

---

## ⚙️ Tech Stack

| Technology | Purpose |
|----------|--------|
| Node.js | Backend runtime |
| Express.js | API framework |
| MongoDB | Database |
| Mongoose | ODM |
| JWT | Authentication |
| bcrypt | Password hashing |

---

## 📌 API Endpoints

### 🔹 Register User
`POST /api/auth/register`

### 🔹 Login User
`POST /api/auth/login`

### 🔹 Access Protected Route
`GET /api/auth/profile`

Requires:

Authorization: Bearer <token>


---

## 🔐 Security Features

- Passwords stored using **hashed encryption**
- Stateless authentication using **JWT**
- Route protection using **middleware**
- Token validation & expiration handling

---

## ▶️ Run Locally

```bash
git clone https://github.com/shaman280306/banking-jwt-auth-api.git
cd banking-jwt-auth-api
npm install
npm run dev
