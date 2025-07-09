# ✨ Fullstack Chat & Video Calling App ✨

A powerful full-stack **Chat & Video Calling Application** designed for real-time communication and immersive interaction. Whether you're collaborating, connecting, or learning languages – this app has it all!

![App Screenshot](https://via.placeholder.com/1000x400.png?text=Your+App+Screenshot)

---

## 🚀 Highlights

- 🌐 **Real-time Messaging** with Typing Indicators, Reactions, and Read Receipts
- 📹 **1-on-1 & Group Video Calls** with Screen Sharing and Recording
- 🔐 **JWT Authentication** with Secure Protected Routes
- 🌍 **Language Exchange Mode** with 32 Unique UI Themes
- ⚡ **Modern Tech Stack**: React + Express + MongoDB + TailwindCSS + TanStack Query
- 🧠 **Global State Management** using Zustand
- 🚨 Full **Error Handling** on both Frontend & Backend
- 🔊 **Audio/Video Recording & Playback**
- 🌐 **WebSocket**-based Real-time Updates via [Stream](https://getstream.io/)
- 🌈 **Dark/Light Mode + Theme Selector**
- 💻 **Responsive UI** for Mobile, Tablet, and Desktop
- 🧪 **Unit-tested Core Components**
- ☁️ **Free Deployment** via Render/Netlify/Vercel

---

## 📁 Project Structure

root/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── hooks/
│ │ ├── context/
│ │ └── App.jsx
├── .env (example below)
└── README.md


## 🔧 .env Configuration

### Backend (`/backend`)
```env
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_stream_api_key
STEAM_API_SECRET=your_stream_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development

### Frontend (/frontend)
env

VITE_STREAM_API_KEY=your_stream_api_key
