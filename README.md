# 🚀 Lark!

<div align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-22-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Express](https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Realtime-010101?style=for-the-badge&logo=socket.io)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?style=for-the-badge)
![Gemini](https://img.shields.io/badge/AI-Google_Gemini-4285F4?style=for-the-badge&logo=google)
![ImageKit](https://img.shields.io/badge/ImageKit-Media-0F8BFF?style=for-the-badge)

<h2>Lark</h2>

A Modern Full-Stack Real-Time Messaging Platform inspired by **WhatsApp**, **Telegram**, and **Messenger**, featuring an integrated **Gemini AI Assistant**.

</div>

---

# 📖 About

Lark is a modern full-stack messaging application built with the **MERN Stack**. It offers secure authentication, real-time communication, AI-powered conversations, cloud-based media sharing, and a responsive user experience.

The application is designed with a scalable architecture by separating the frontend and backend, making it suitable for production-ready deployment.

---

# 📸 Screenshots

> Create a folder named **screenshots** in the root of the project and place your images there.

## Login

```md
![Login](screenshots/login.png)
```

---

## Home

```md
![Home](screenshots/home.png)
```

---

## AI Assistant

```md
![AI Chat](screenshots/ai-chat.png)
```

---

## Profile Settings

```md
![Profile](screenshots/profile.png)
```

---

## Mobile View

```md
![Mobile](screenshots/mobile-view.png)
```

---

# ✨ Features

- 🔐 JWT Authentication with Email OTP Verification
- 💬 Real-Time One-to-One Messaging
- 🤖 Google Gemini AI Assistant
- 📷 Image, Video, Audio & Document Sharing
- ☁️ ImageKit Cloud Storage
- 😀 Emoji Reactions
- ↩️ Reply to Messages
- 📤 Forward Messages
- ✏️ Edit Messages
- 🗑️ Delete for Me / Delete for Everyone
- 📌 Pin & Unpin Messages
- 🟢 Online/Offline Presence
- ⌨️ Real-Time Typing Indicator
- ✅ Read Receipts
- 👤 Profile Management
- 🎨 Light/Dark Mode & Theme Customization
- 📱 Fully Responsive UI
- 🐳 Docker Ready

---

# 🛠 Tech Stack

## Frontend

- React 19
- Vite
- React Router
- Zustand
- Axios
- Socket.IO Client
- Tailwind CSS
- HeroUI
- Lucide React

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Socket.IO
- Multer
- ImageKit SDK
- Google Gemini API
- node-cron

---

# 📂 Project Structure

```text
Lark/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── lib/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   └── index.js
│   │
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── data/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── styles/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   └── package.json
│
├── Dockerfile
├── README.md
└── screenshots/
```

---

# 🚀 Why Lark?

Lark combines the best features of modern messaging platforms into a single application.

- ⚡ Instant real-time messaging using Socket.IO
- 🤖 Integrated AI assistant powered by Gemini
- 📁 Secure cloud media storage with ImageKit
- 🔐 JWT Authentication with Email OTP
- 🎨 Beautiful and responsive UI
- 🏗️ Clean MERN architecture
- 📱 Mobile-friendly experience
- 🐳 Easy deployment with Docker

---


# ⚙️ Installation

## Prerequisites

Make sure the following are installed on your system:

- Node.js (v20 or later)
- npm
- MongoDB
- Git

---

## Clone the Repository

```bash
git clone https://github.com/vansh-jethwani/Lark.git
cd Lark
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder.

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLIENT_URL=http://localhost:5173

IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint

GEMINI_API_KEY=your_gemini_api_key

NODE_ENV=development
```

Start the backend server.

```bash
npm run dev
```

Backend runs on:

```
http://localhost:3000
```

---

## Frontend Setup

Open another terminal.

```bash
cd frontend
npm install
```

Create a `.env` file inside the `frontend` folder.

```env
VITE_API_URL=http://localhost:3000/api
```

Start the frontend.

```bash
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

# 🐳 Docker

Build the Docker image:

```bash
docker build -t lark .
```

Run the container:

```bash
docker run -p 3000:3000 --env-file backend/.env lark
```

---

# ☁️ Deployment

| Service | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| Database | MongoDB Atlas |
| Media Storage | ImageKit |
| AI | Google Gemini API |

---

# 📜 Available Scripts

## Backend

| Command | Description |
|----------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start development server |
| `npm start` | Start production server |

---

## Frontend

| Command | Description |
|----------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start Vite development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

---

# 🛣️ Roadmap

Planned features for future releases:

- 📞 Voice Calling
- 🎥 Video Calling
- 👥 Group Chats
- 🔍 Message Search
- ⭐ Starred Messages
- 🔐 End-to-End Encryption
- 🤖 AI Image Generation

---

# 👨‍💻 Author

**Vansh Jethwani**

Computer Science Undergraduate passionate about Full-Stack Development, Backend Engineering, Artificial Intelligence, Cloud Computing, and DevOps.

**GitHub**

```text
https://github.com/vansh-jethwani
```

**Project Repository**

```text
https://github.com/vansh-jethwani/Lark
```

---

# 📄 License

This project is licensed under the **ISC License**.

Feel free to use, modify, and learn from this project for educational purposes.

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a star!

Made with ❤️ by **Vansh Jethwani**

</div>
