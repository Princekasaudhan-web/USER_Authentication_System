<p align="center">
  <img src="assets/banner.png" alt="User Authentication System Banner" width="100%">
</p>

# 🔐 User Authentication System

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![bcrypt](https://img.shields.io/badge/bcrypt-00599C?style=for-the-badge)

A secure REST API built with **Node.js**, **Express.js**, **MongoDB**, **JWT**, and **bcrypt**. This project demonstrates user authentication, password hashing, JWT-based authorization, and protected routes.

---

# 🚀 Features

- ✅ User Signup
- ✅ User Login
- ✅ JWT Authentication
- ✅ Protected Routes
- ✅ Password Hashing with bcrypt
- ✅ MongoDB Database
- ✅ Environment Variables
- ✅ REST API
- ✅ Error Handling

---

# 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- dotenv
- Postman

---

# 📁 Project Structure

```text
USER_Authentication_System/
│
├── assets/
│   ├── banner.png
│   └── screenshots/
│       ├── get-users.png
│       ├── login.png
│       └── register.png
│
├── config/
│   └── db.js
│
├── controllers/
│   └── authController.js
│
├── middleware/
│   └── authMiddleware.js
│
├── models/
│   └── User.js
│
├── routes/
│   └── authRoutes.js
│
├── .env
├── .gitignore
├── package.json
├── server.js
└── README.md
```

---

# ⚙️ Installation

## Clone the repository

```bash
git clone https://github.com/Princekasaudhan-web/USER_Authentication_System.git
```

## Navigate to the project

```bash
cd USER_Authentication_System
```

## Install dependencies

```bash
npm install
```

## Create a `.env` file

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
JWT_EXPIRE=7d
```

## Start the server

```bash
npm run dev
```

---

# 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/signup` | Register a New User |
| POST | `/api/auth/login` | Login User |
| GET | `/api/auth/profile` | Get Logged-in User Profile |

---

# 🔐 Authentication

For protected routes, include the JWT token in the request header.

```text
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjZhNTI3MTNkYTM3ZjQ0MDkxZTE0OWIwOCIsImlhdCI6MTc4Mzc4ODY3MSwiZXhwIjoxNzgzNzkyMjcxfQ.yRIAAha4YErP3Y9Pa8W1jGMVR85RZz4CV8J3ZPHGkgo
```

---

# 📸 API Screenshots

## 👤 User Registration

![Register](assets/screenshots/register.png)

---

## 🔑 User Login

![Login](assets/screenshots/login.png)

---

## 👤 User Profile (Protected Route)

![Profile](assets/screenshots/profile.png)

---

# 🔒 Security Features

- Password Hashing using bcrypt
- JWT Authentication
- Protected Routes
- Environment Variables
- Secure Password Storage

---

# 📈 Future Improvements

- Email Verification
- Forgot Password
- Reset Password
- Role-Based Authorization
- Refresh Tokens
- Swagger API Documentation
- Docker Support
- Unit Testing with Jest

---

# 👨‍💻 Author

**Prince**

GitHub:  
https://github.com/Princekasaudhan-web

---

# ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub!