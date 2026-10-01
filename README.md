# Connecta – Video Conferencing Platform

Connecta is a modern video conferencing application built with the MERN stack. It enables users to create and join video meetings with authentication, a responsive interface, and real-time communication.

## 🌐 Live Demo

* **Frontend:** https://connecta-frontend-hugd.onrender.com
* **Backend API:** https://connecta-backend-74k5.onrender.com

---

## ✨ Features

* 🔐 User Authentication
* 📹 Create and Join Video Meetings
* 👥 Secure Meeting Rooms
* ⚡ Real-Time Video & Audio Communication
* 🎨 Modern Responsive UI
* 📱 Mobile-Friendly Design
* 🚀 Fast and Scalable Architecture

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* JavaScript

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Authentication

* Clerk Authentication

### Video Streaming

* Stream Video SDK

### Database

* MongoDB Atlas

---

## 📂 Project Structure

```text
Connecta/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── package.json
│
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/VijayMalan/-Connecta.git
cd Connecta
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file inside the `backend` directory.

```env
MONGO_URI=your_mongodb_uri
CLERK_SECRET_KEY=your_clerk_secret
STREAM_API_KEY=your_stream_api_key
STREAM_SECRET=your_stream_secret
```

Create a `.env` file inside the `frontend` directory.

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_STREAM_API_KEY=your_stream_api_key
```

**Never commit `.env` files or API secrets to GitHub.**

---

## 📸 Screenshots

The application includes:

* Home Page
* Login Page
* Dashboard
* Video Meeting Room

---

## 📈 Future Improvements

* Chat during meetings
* Screen Sharing
