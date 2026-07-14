<p align="center">
  <img src="assets/banner.png" alt="User Authentication System Banner" width="100%">
</p>
# 🔐 User Authentication System

A secure and scalable REST API built using **Node.js**, **Express.js**, **MongoDB**, **JWT**, and **bcrypt**.

---

## 🚀 Features

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Password Hashing
- Role-Based Authorization
- Email Validation
- Password Validation
- Logout API
- CRUD Operations
- MongoDB Integration
- REST API

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- dotenv

---

## 📂 Project Structure

```text
config/
controllers/
middleware/
models/
routes/
server.js
package.json
```

---

## ⚙️ Installation

```bash
git clone https://github.com/Princekasaudhan-web/USER_Authentication_System.git
```

```bash
cd USER_Authentication_System
```

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_database_url
JWT_SECRET=your_secret_key
```

Run the server:

```bash
npm run dev
```

---

## 🔐 Authentication

Use JWT Token:

```text
Authorization: Bearer YOUR_TOKEN
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register User |
| POST | /api/auth/login | Login User |
| POST | /api/auth/logout | Logout |
| GET | /api/users | Get All Users |
| GET | /api/users/:id | Get User |
| PUT | /api/users/:id | Update User |
| DELETE | /api/users/:id | Delete User |

---

## 📈 Future Improvements

- Email Verification
- Forgot Password
- Reset Password
- Refresh Token
- Docker Support
- Swagger Documentation
- Unit Testing

---

## 👨‍💻 Author

**Prince Kasaudhan**

GitHub:
https://github.com/Princekasaudhan-web

⭐ If you like this project, give it a star.
