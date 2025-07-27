# Realtime-Chat-App

A full-stack real-time chat application built with **React** and **Firebase**, supporting secure user authentication, real-time messaging, media sharing, and online presence tracking, Dockerized for easy setup and deployment.

## Features

- **User Authentication**
  - Sign up, log in, and log out securely via Firebase Authentication
  - Password reset via email

- **User Search**
  - Search users by their username
  - Initiate new chat conversations seamlessly

- **Real-Time Messaging**
  - One-to-one chat with real-time updates using Firestore listeners
  - Smooth and responsive chat interface with timestamp support

- **Media Sharing**
  - Send images in chat
  - All shared media organized in a dedicated Media section

- **Online Presence Tracking**
  - Tracks and updates online status every 60 seconds

## Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- React Hooks

**Backend:**
- Firebase Authentication
- Cloud Firestore (for chat + user data)
- Firebase Storage (for media)
- **Dockerized Setup**
  - Easily run the entire frontend locally in seconds using Docker

---

## 🐳 Docker Usage

You can run this project using Docker with just a few commands.

### 1. Clone the Repository

```bash or pwsh (your choice)
git clone https://github.com/shreeraamvishaal/Realtime-Chat-App.git
cd Realtime-Chat-App/chat-app
docker build -t realtime-chat-app .
docker run -d -p 3000:80 realtime-chat-app
```

Built by Shree Raam Vishaal K  
connect with me on (Linkedin)[https://www.linkedin.com/in/shree-raam-vishaal-1b6128263/]
Feel free to reachout to me at shreeraamvishaal@gmail.com
