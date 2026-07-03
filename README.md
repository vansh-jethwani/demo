# 🚀 Lark

<div align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-22-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Express](https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Realtime-010101?style=for-the-badge&logo=socket.io)
![JWT](https://img.shields.io/badge/Auth-JWT-orange?style=for-the-badge)
![Gemini](https://img.shields.io/badge/AI-Google_Gemini-4285F4?style=for-the-badge&logo=google)
![ImageKit](https://img.shields.io/badge/ImageKit-Media-0F8BFF?style=for-the-badge)

<h3>A Modern Full-Stack Real-Time Messaging Platform</h3>

Inspired by **WhatsApp**, **Telegram**, and **Messenger**, with an integrated **Gemini AI Assistant**.

</div>

---

# 📖 About

**Lark** is a modern full-stack chat application built using the **MERN Stack**. It provides a fast, secure, and responsive messaging experience with real-time communication powered by **Socket.IO**.

Unlike a basic chat application, Lark includes modern messaging features such as:

- 🤖 AI-powered conversations using Google Gemini
- 🔐 JWT Authentication with Email OTP Verification
- 📷 Media sharing
- 😀 Emoji reactions
- 📌 Message pinning
- ✏️ Message editing
- 🗑️ Delete for Me / Delete for Everyone
- 📤 Forward messages
- ↩️ Reply to messages
- 👤 Profile management
- 🎨 Theme customization
- 📱 Fully responsive interface

The project follows a scalable MERN architecture with completely separate frontend and backend codebases.

---

# ✨ Features

## 🔐 Authentication

- JWT Authentication
- Email OTP Verification
- Secure Password Hashing
- Protected Routes
- Persistent Login
- Logout Support

---

## 💬 Messaging

- One-to-One Chat
- Real-Time Messaging
- Instant Message Delivery
- Read Receipts
- Seen Status
- Online / Offline Status
- Typing Indicator
- Conversation Sorting
- Latest Chat on Top

---

## 📝 Advanced Message Features

- Reply to Messages
- Forward Messages
- Edit Messages
- Delete for Me
- Delete for Everyone
- Emoji Reactions
- Pin Messages
- Multiple Pinned Messages
- Context Menu
- Selection Mode

---

## 📂 Media Sharing

- Images
- Videos
- Audio Files
- Documents
- Media Preview
- Download Media
- ImageKit Cloud Storage

---

## 🤖 AI Assistant

- Powered by Google Gemini
- Dedicated AI Conversation
- AI Chat History
- Instant Responses
- Modern AI Interface

---

## 👤 User Profile

- Edit Profile
- Change Profile Picture
- Update Name
- Update Username
- Bio
- Delete Account
- Profile Settings

---

## 🎨 User Experience

- Responsive Design
- Dark Theme
- Light Theme
- Multiple Theme Presets
- Smooth Animations
- Beautiful UI
- Mobile Friendly

---

## ⚡ Real-Time Features

- Socket.IO Integration
- Live Messaging
- Live User Presence
- Live Typing
- Instant Message Updates
- Automatic Conversation Refresh

---

## 🔒 Security

- JWT Authentication
- Password Hashing
- Protected APIs
- Secure File Upload
- Authentication Middleware
- Input Validation

---

# 🛠 Tech Stack

## 🎨 Frontend

- React 19
- Vite
- React Router
- Zustand
- Axios
- Socket.IO Client
- HeroUI
- Tailwind CSS
- Lucide React

---

## ⚙️ Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Socket.IO
- Multer
- ImageKit SDK
- Google Gemini API
- node-cron
- dotenv
- CORS

---

# 📂 Project Structure

```text
Lark/
├── .dockerignore
├── .gitignore
├── backend/
│   ├── package.json
│   ├── package-lock.json
│   └── src/
│       ├── controllers/
│       │   ├── ai.controller.js
│       │   ├── auth.controller.js
│       │   ├── message.controller.js
│       │   └── profile.controller.js
│       │
│       ├── lib/
│       │   ├── cron.js
│       │   ├── db.js
│       │   ├── gemini.js
│       │   ├── imagekit.js
│       │   └── socket.js
│       │
│       ├── middlewares/
│       │   ├── auth.middleware.js
│       │   └── upload.middleware.js
│       │
│       ├── models/
│       │   ├── aiMessage.model.js
│       │   ├── message.model.js
│       │   └── user.model.js
│       │
│       ├── routes/
│       │   ├── ai.routes.js
│       │   ├── auth.routes.js
│       │   ├── message.routes.js
│       │   └── profile.routes.js
│       │
│       └── index.js
│
├── frontend/
│   ├── public/
│   │   ├── auth.png
│   │   ├── favicon.png
│   │   ├── icons.svg
│   │   └── logo.png
│   │
│   ├── package.json
│   ├── vite.config.js
│   │
│   └── src/
│       ├── components/
│       │   ├── auth/
│       │   ├── chat/
│       │   └── profile/
│       │
│       ├── context/
│       ├── data/
│       ├── hooks/
│       ├── lib/
│       ├── pages/
│       ├── store/
│       ├── styles/
│       ├── App.jsx
│       ├── main.jsx
│       └── index.css
│
├── Dockerfile
└── README.md
```

---

# 📸 Application Screenshots

> Add screenshots of your application inside a **screenshots/** folder.

```text
screenshots/
│
├── login.png
├── signup.png
├── home.png
├── ai-chat.png
├── profile.png
├── media-sharing.png
├── themes.png
├── mobile-view.png
└── demo.gif
```

Example:

```md
## Login

![Login](screenshots/login.png)

## Home

![Home](screenshots/home.png)

## AI Assistant

![AI](screenshots/ai-chat.png)
```

---

# 🌟 Key Highlights

- 🚀 WhatsApp-like User Experience
- 🤖 Gemini AI Integration
- ⚡ Socket.IO Real-Time Communication
- ☁️ ImageKit Cloud Media Storage
- 🔐 JWT Authentication with Email OTP
- 📱 Fully Responsive UI
- 🎨 Multiple Themes
- 🛠 Modular MERN Architecture
- 🐳 Docker Ready
- 📂 Clean Folder Structure

---


# 🚀 Getting Started

## 📋 Prerequisites

Make sure you have the following installed before running the project:

- Node.js (v20 or later)
- npm
- MongoDB
- Git
- ImageKit Account
- Google Gemini API Key

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/vansh-jethwani/Lark.git
cd Lark
```

---

## 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the **backend** folder.

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_super_secret_key

CLIENT_URL=http://localhost:5173

IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=

GEMINI_API_KEY=

NODE_ENV=development
```

Start the backend server.

```bash
npm run dev
```

Backend will run on

```
http://localhost:3000
```

---

## 3️⃣ Frontend Setup

Open another terminal.

```bash
cd frontend
npm install
```

Create a `.env` file.

```env
VITE_API_URL=http://localhost:3000/api
```

Run the frontend.

```bash
npm run dev
```

Frontend will run on

```
http://localhost:5173
```

---

# 📁 Folder Explanation

## Backend

### controllers/

Contains all business logic.

- Authentication
- Messages
- AI
- Profile

---

### lib/

Contains reusable services.

- MongoDB connection
- Socket.IO
- ImageKit
- Gemini
- Cron jobs

---

### middlewares/

Contains middleware functions.

- JWT Authentication
- File Upload

---

### models/

Contains MongoDB models.

- User
- Message
- AI Message

---

### routes/

Defines all REST API routes.

---

## Frontend

### components/

Reusable UI components.

Contains

- Authentication Components
- Chat Components
- Profile Components

---

### pages/

Contains complete pages.

- Authentication
- Chat
- Profile Settings

---

### context/

Theme Context.

---

### hooks/

Reusable React Hooks.

---

### store/

Zustand global state management.

---

### lib/

Axios configuration.

Utility functions.

ImageKit helper.

---

### styles/

Custom HeroUI themes.

---

# 🔄 Application Flow

```text
User
 │
 ▼
Signup/Login
 │
 ▼
Email OTP Verification
 │
 ▼
JWT Token Generated
 │
 ▼
JWT Stored in Browser
 │
 ▼
Protected API Request
 │
 ▼
Backend Authentication Middleware
 │
 ▼
MongoDB
 │
 ▼
Socket.IO Connection
 │
 ▼
Conversation List
 │
 ▼
Open Chat
 │
 ▼
Load Messages
 │
 ▼
Realtime Messaging
 │
 ▼
ImageKit Uploads
 │
 ▼
Gemini AI (Optional)
 │
 ▼
Realtime Updates
```

---

# 📡 REST API

## Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/auth/signup` | Register a new user |
| POST | `/api/auth/login` | Login |
| POST | `/api/auth/logout` | Logout |
| POST | `/api/auth/send-otp` | Send Email OTP |
| POST | `/api/auth/verify-otp` | Verify OTP |
| GET | `/api/auth/check` | Verify JWT |

---

## Messages

| Method | Endpoint |
|---------|----------|
| GET | `/api/messages/users` |
| GET | `/api/messages/conversations` |
| GET | `/api/messages/:id` |
| POST | `/api/messages/send/:id` |
| PATCH | `/api/messages/edit/:id` |
| DELETE | `/api/messages/delete/:id` |
| PATCH | `/api/messages/read/:id` |
| PATCH | `/api/messages/pin/:id` |
| PATCH | `/api/messages/reaction/:id` |
| POST | `/api/messages/forward` |

---

## AI

| Method | Endpoint |
|---------|----------|
| POST | `/api/ai/chat` |
| GET | `/api/ai/history` |

---

## Profile

| Method | Endpoint |
|---------|----------|
| GET | `/api/profile` |
| PATCH | `/api/profile` |
| DELETE | `/api/profile` |

---

# ⚡ Socket.IO Events

## Client → Server

| Event | Purpose |
|---------|---------|
| sendMessage | Send new message |
| typing | Typing indicator |
| stopTyping | Stop typing |

---

## Server → Client

| Event | Purpose |
|---------|---------|
| newMessage | Receive message |
| messageEdited | Message edited |
| messageDeleted | Message deleted |
| reactionUpdated | Emoji reaction updated |
| pinUpdated | Pin/unpin message |
| typing | User typing |
| stopTyping | User stopped typing |
| onlineUsers | Online user list |

---

# 🧠 AI Assistant

Lark includes an integrated **Gemini AI Assistant**.

Features include:

- Dedicated AI conversation
- Instant responses
- Persistent AI chat history
- Context-aware conversations
- Clean AI interface

---

# 📤 Media Sharing

Supported media types

- Images
- Videos
- Audio
- Documents

Features

- Preview before sending
- Cloud upload using ImageKit
- Download media
- In-chat media player

---

# 🎨 Theme System

Users can personalize the application with:

- Light Mode
- Dark Mode
- HeroUI Theme Presets
- Accent Colors
- Smooth Theme Switching

---

# 👤 Profile Management

Users can

- Change profile picture
- Update name
- Update username
- Edit bio
- Delete account
- Manage profile settings

---

# 🔒 Security

Lark follows several security practices.

- JWT Authentication
- Password Hashing
- Protected Routes
- Authentication Middleware
- Secure File Upload
- Input Validation
- MongoDB Validation
- Environment Variables
- CORS Protection

---

# 📊 Database Collections

```text
users

messages

aiMessages
```

---

# 💾 Media Storage

Lark uses **ImageKit** for media storage.

Benefits

- Fast CDN
- Optimized delivery
- Secure uploads
- Scalable storage

---


# 🐳 Docker

Lark is Docker-ready and can be containerized for deployment.

## Build Docker Image

```bash
docker build -t lark .
```

---

## Run Docker Container

```bash
docker run -p 3000:3000 --env-file backend/.env lark
```

---

# ☁️ Deployment

You can deploy the project using the following services.

## Frontend

- Vercel
- Netlify

---

## Backend

- Render
- Railway
- DigitalOcean

---

## Database

- MongoDB Atlas

---

## Media Storage

- ImageKit

---

## AI

- Google Gemini API

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

# 📈 Performance

Lark is designed to provide a fast and responsive messaging experience.

### Optimizations

- Socket.IO Real-Time Communication
- Zustand Global State Management
- Optimized React Rendering
- ImageKit CDN
- Lazy Loading Components
- Efficient MongoDB Queries
- Reusable Components
- Modular Architecture

---

# 🚀 Future Roadmap

The following features are planned for future releases.

### Communication

- 📞 Voice Calling
- 🎥 Video Calling
- 👥 Group Chats
- 📢 Broadcast Messages
- 📺 Screen Sharing

---

### Messaging

- Message Search
- Starred Messages
- Scheduled Messages
- Disappearing Messages
- Polls
- Stickers
- GIF Support

---

### AI

- AI Image Generation
- AI Voice Assistant
- Smart Replies
- Conversation Summaries
- AI Translation

---

### Security

- End-to-End Encryption
- Two-Factor Authentication (2FA)
- Login Activity
- Device Management

---

### Productivity

- Calendar Integration
- File Manager
- Cloud Backup
- Desktop Notifications

---

# 🧪 Project Highlights

✔ Modern MERN Architecture

✔ JWT Authentication

✔ Email OTP Verification

✔ Google Gemini AI

✔ Socket.IO Realtime Messaging

✔ ImageKit Media Storage

✔ Responsive UI

✔ Advanced Message Features

✔ Profile Management

✔ Theme Customization

✔ Docker Support

---

# 📸 Recommended Screenshots

For the best GitHub presentation, add the following screenshots.

```
screenshots/
│
├── login.png
├── signup.png
├── otp.png
├── home.png
├── sidebar.png
├── ai-chat.png
├── media-sharing.png
├── reply.png
├── reactions.png
├── pinned-message.png
├── profile-settings.png
├── themes.png
├── mobile-view.png
└── demo.gif
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 🐞 Reporting Issues

If you encounter any bugs or have suggestions for improvements:

- Open an issue on GitHub.
- Clearly describe the problem.
- Include screenshots if possible.
- Mention steps to reproduce the issue.

---

# 🙏 Acknowledgements

Special thanks to the technologies that power Lark.

- React
- Vite
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- HeroUI
- Tailwind CSS
- Zustand
- ImageKit
- Google Gemini API

---

# 📚 Learning Objectives

Lark was built to gain hands-on experience with:

- Full-Stack MERN Development
- REST API Design
- Authentication using JWT
- Email OTP Verification
- Real-Time Communication
- Socket.IO
- Cloud Media Storage
- AI Integration
- State Management
- Docker
- Responsive UI Design

---

# 👨‍💻 Author

## Vansh Jethwani

Computer Science Undergraduate

Passionate about

- Full Stack Development
- Backend Engineering
- Artificial Intelligence
- Cloud Computing
- DevOps

GitHub

```
https://github.com/vansh-jethwani
```

Project Repository

```
https://github.com/vansh-jethwani/Lark
```

---

# ⭐ Support the Project

If you found this project useful,

⭐ Star the repository

🍴 Fork it

🛠 Contribute

📢 Share it with others

Your support motivates future improvements.

---

# 📄 License

This project is licensed under the **ISC License**.

Feel free to use, modify, and learn from this project for educational purposes.

---

<div align="center">

# 🚀 Thank You for Visiting Lark

### If you like this project, don't forget to ⭐ Star the repository!

Made with ❤️ by **Vansh Jethwani**

</div>
