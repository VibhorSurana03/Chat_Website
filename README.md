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
- **Group Channels** - Create and manage group conversations with multiple members
- **Message Persistence** - All messages stored in MongoDB for chat history
- **Real-Time Updates** - Instant message delivery to all connected users

### 🎮 **Integrated Gaming**
- **Chess Integration** - Quick access to external chess platform (chess.gain.gg)
- **Game Invitations** - Send chess game invites directly in chat
- **Game Tracking** - Store game information in database
- **Easy Access** - One-click game launch from chat interface

### 🎨 **Modern UI/UX**
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Dark Theme** - Modern dark interface for comfortable viewing
- **Emoji Picker** - Full emoji support with emoji-picker-react
- **File Sharing** - Upload and share images and files in conversations
- **Profile Customization** - Set profile pictures, names, and color themes
- **Tabbed Interface** - Easy navigation between login and signup

### 🔐 **Security & Authentication**
- **JWT Authentication** - Secure token-based authentication with 3-day expiry
- **Password Encryption** - Bcrypt hashing with salt for user passwords
- **Protected Routes** - Middleware-based route protection (verifyToken)
- **Secure Cookies** - HTTP-only cookies with SameSite=None for cross-origin
- **Profile Setup Flow** - Guided onboarding after registration

---

## 🛠️ Tech Stack

### **Frontend**
- **React 18.3** - Modern UI library with hooks
- **Vite** - Lightning-fast build tool and dev server
- **TailwindCSS** - Utility-first CSS framework
- **Shadcn/ui** - Beautiful, accessible component library (Avatar, Dialog, Tabs, etc.)
- **Socket.io Client 4.7** - Real-time bidirectional communication
- **Zustand 4.5** - Lightweight state management
- **React Router 6.26** - Client-side routing
- **Axios 1.7** - HTTP client for API calls
- **Emoji Picker React** - Full-featured emoji picker
- **React Icons** - Icon library for UI elements
- **Moment.js** - Date and time formatting

### **Backend**
- **Node.js & Express 4.19** - Fast, minimalist web framework
- **Socket.io 4.7** - Real-time WebSocket server
- **MongoDB & Mongoose 8.5** - NoSQL database with ODM
- **JWT (jsonwebtoken 9.0)** - JSON Web Token authentication
- **Bcrypt 5.1** - Password hashing with salt
- **Multer 1.4** - File upload handling
- **CORS 2.8** - Cross-origin resource sharing
- **Cookie Parser** - Parse and manage cookies
- **Dotenv** - Environment variable management

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
   PORT=8747
   JWT_KEY=your_jwt_secret_key
   ORIGIN=http://localhost:5173
   DATABASE_URL=your_mongodb_connection_string
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

---

## 👨‍💻 Developer

**Vibhor Surana**

- GitHub: [@VibhorSurana03](https://github.com/VibhorSurana03)
- Email: vibhorsurana03@gmail.com

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

</div>
