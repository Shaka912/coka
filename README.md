# 🥤 Coka Dating App – Backend

This is the backend server for the **Coka Dating App**, built with **Node.js**, **Express**, and **MongoDB**. It serves as the API layer for managing user authentication, matchmaking, messages, profiles, and more.

---

## 🚀 Tech Stack

- **Node.js**
- **Express**
- **MongoDB** (Mongoose ODM)
- **Dotenv** for environment configs
- **CORS** for cross-origin requests
- **JWT** for secure authentication

---
## 📁 Project Structure


coka-dating-backend/
├── controllers/ # Route controllers for handling logic
├── models/ # Mongoose schemas/models
├── routes/ # Express route definitions
├── middleware/ # Custom middleware (e.g., auth, error handling)
├── config/ # MongoDB connection config
├── utils/ # Utility functions (e.g., token generation)
├── .env # Environment variables
├── index.js # Entry point
├── package.json



✅ Features
JWT-based Auth

Secure password hashing (bcrypt)

User matchmaking logic

Realtime (planned): WebSocket or Socket.IO

Modular and scalable folder structure

Socket.IO for live chat

Push notifications integration

Admin dashboard APIs

Testing (Jest or Mocha)
