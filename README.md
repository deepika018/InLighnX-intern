# ✨ Fullstack Chat & Video Calling App ✨

A powerful full-stack **Chat & Video Calling Application** designed for real-time communication and immersive interaction. Whether you're collaborating, connecting, or learning languages – this app has it all!

![image](https://github.com/user-attachments/assets/7e621f59-ee99-4d64-b3bc-b9a50e7b9c2d)

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

# ✨ Frontend – Chat & Video Calling App

This is the **Frontend** part of the Fullstack Chat & Video Calling App built using **React**, **TailwindCSS**, and **TanStack Query**. It supports real-time messaging, video calls, and dynamic theming, powered by Zustand for state management and the Stream API for WebSocket messaging.

---

## 🔥 Key Features

- 💬 Real-time chat with emoji reactions and typing indicators  
- 📞 1-on-1 and group video calling with screen sharing and recording  
- 🎨 32 beautiful UI themes with dark/light mode  
- 🌍 Language exchange mode with live switching  
- 🔒 JWT-based secure route access  
- ⚡ Optimized state and data fetching with Zustand + TanStack Query  
- 🚨 Frontend error boundaries and toast notifications  
- 📱 Fully responsive for mobile, tablet, and desktop  

---

## 📦 Tech Stack

| Technology       | Purpose                    |
|------------------|-----------------------------|
| React            | Frontend UI                |
| TailwindCSS      | Styling                    |
| TanStack Query   | Data fetching & caching    |
| Zustand          | Global state management    |
| Stream API       | Real-time messaging        |
| React Router     | Routing                    |
| Vite             | Fast dev environment       |

---

## 🔧 Environment Setup

Create a `.env` file in the `/frontend` directory:

```env
VITE_STREAM_API_KEY=your_stream_api_key

