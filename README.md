# 💬 Real-Time Chat Application with Integrated Gaming

<div align="center">

![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-Real--Time-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**A modern, feature-rich real-time chat platform with integrated gaming capabilities**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [Demo](#-demo)

</div>

---

## 🚀 Features

### 💬 **Real-Time Communication**
- **Instant Messaging** - Lightning-fast message delivery using WebSocket technology
- **Direct Messages** - Private one-on-one conversations
- **Group Channels** - Create and manage group conversations
- **Online Status** - See who's online in real-time
- **Typing Indicators** - Know when someone is typing

### 🎮 **Integrated Gaming**
- **Chess Game** - Play chess with your chat partners directly in the app
- **Real-time Gameplay** - Synchronized game state across players
- **Interactive UI** - Beautiful chessboard with drag-and-drop functionality

### 🎨 **Modern UI/UX**
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Dark/Light Mode** - Eye-friendly themes for any environment
- **Emoji Support** - Express yourself with emoji picker
- **File Sharing** - Share images and files in conversations
- **Message History** - Persistent chat history with MongoDB

### 🔐 **Security & Authentication**
- **JWT Authentication** - Secure token-based authentication
- **Password Encryption** - Bcrypt hashing for user passwords
- **Protected Routes** - Middleware-based route protection
- **Cookie Management** - Secure HTTP-only cookies

---

## 🛠️ Tech Stack

### **Frontend**
- **React 18.3** - Modern UI library with hooks
- **Vite** - Lightning-fast build tool
- **TailwindCSS** - Utility-first CSS framework
- **Shadcn/ui** - Beautiful, accessible component library
- **Socket.io Client** - Real-time bidirectional communication
- **Zustand** - Lightweight state management
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Chess.js & React-Chessboard** - Chess game implementation

### **Backend**
- **Node.js & Express** - Fast, minimalist web framework
- **Socket.io** - Real-time WebSocket server
- **MongoDB & Mongoose** - NoSQL database with ODM
- **JWT** - JSON Web Token authentication
- **Bcrypt** - Password hashing
- **Multer** - File upload handling
- **CORS** - Cross-origin resource sharing

---

## 📦 Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)

### Clone the Repository
```bash
git clone https://github.com/VibhorSurana03/Chat_Website.git
cd Chat_Website
```

### Server Setup
1. Navigate to the server directory:
   ```bash
   cd server
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with the following variables:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ORIGIN=http://localhost:5173
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

### Client Setup
1. Navigate to the client directory:
   ```bash
   cd ../client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with:
   ```env
   VITE_SERVER_URL=http://localhost:5000
   ```

4. Start the client:
   ```bash
   npm run dev
   ```

5. Open your browser and visit `http://localhost:5173`

---

## 🎯 Usage

1. **Sign Up** - Create a new account with email and password
2. **Login** - Access your account securely
3. **Start Chatting** - Create channels or send direct messages
4. **Play Games** - Challenge friends to a chess match
5. **Share Files** - Upload and share images/files in conversations

---

## 📸 Demo

The application features:
- Clean, modern interface with intuitive navigation
- Real-time message updates without page refresh
- Smooth animations and transitions
- Responsive design that works on all devices
- Integrated chess game with real-time synchronization

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

## 📝 License

This project is open source and available under the MIT License.

---

## 👨‍💻 Developer

**Vibhor Surana**

- GitHub: [@VibhorSurana03](https://github.com/VibhorSurana03)
- Email: vibhorsurana03@gmail.com

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

Made with ❤️ by Vibhor Surana

</div>
