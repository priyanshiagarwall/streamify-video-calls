# 💬 Full Stack Social Chat App (React + Node + MongoDB)

A full-stack social media + chat application built with **React**, **Node.js**, **Express**, **MongoDB**, and **Stream**.  
Features include authentication, onboarding, friends system, real-time chat, notifications, video calls, theming, and more.

This project is built step-by-step following a complete tutorial series, covering both backend and frontend in depth.

---

## 🚀 Features

- 🔐 Authentication (Signup, Login, Logout)
- 🧑‍💼 User Onboarding
- 🤝 Friend System (Send / Accept Requests)
- 👥 Recommended Users & Friends
- 💬 Real-time Chat
- 🔔 Notifications
- 🎨 Theme Selector
- 🏠 Home Feed
- 📹 Video Calls
- ⚡ TanStack Query for Data Fetching

---

## 🛠 Tech Stack

### Frontend
- React
- TanStack Query
- React Router
- CSS / Tailwind (if used)
- Stream Chat SDK

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- Stream API

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone 
cd your-repo-name


2️⃣ Setup Backend

cd backend
npm install


Create a .env file in backend/:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

Run Backend:
npm run dev


3️⃣ Setup Frontend
cd frontend
npm install
npm run dev
