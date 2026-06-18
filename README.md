
# 🚀 MeetSpace — Real-Time Video Conferencing Platform

A full-stack, real-time video conferencing web application built using the MERN stack and WebRTC. MeetSpace enables seamless peer-to-peer video communication with features like multi-user rooms, screen sharing, and in-call messaging — all optimized for low latency and high reliability.

---


## 📌 Features

- 🎥 Real-Time Video & Audio Streaming (WebRTC)
- 👥 Multi-User Room Support (dynamic join/create rooms)
- 💬 In-Call Chat (Socket.io)
- 🖥️ Screen Sharing
- 🔄 Dynamic Peer Connection Handling
- 🌍 STUN/TURN Network Optimization
- 🔐 Scalable MERN Backend

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS *(if used)*
- WebRTC APIs

### Backend
- Node.js
- Express.js
- Socket.io (Signaling Server)

### Database
- MongoDB

### Other
- WebRTC (P2P Communication)
- STUN/TURN Servers (NAT Traversal)

---

## 🏗️ Architecture

Client (React) → Socket.io (Signaling) → WebRTC (P2P) → Media Streaming

- Socket.io handles signaling (offer, answer, ICE candidates)
- WebRTC manages peer-to-peer connection
- MongoDB stores room/user data (optional)

---

## ⚙️ Setup Instructions

### 1. Clone Repo
git clone https://github.com/Sarthaktanpure/MeetSpace
cd meetspace
