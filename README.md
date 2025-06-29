# Sandesh  (Instant  Chat App)

A real-time, HIPAA-esque text chat system  built with React, Node.js, and powered by Stream (GetStream.io).

---

## 🎯 Features

- **Staff Authentication** – Secure login for medical professionals.
- **Real-time Messaging** – Instant one-on-one and group chat functionality.
- **Activity Notifications** – Real-time updates when new messages arrive.
- **Responsive UI** – Clean, mobile-friendly interface built with Stream’s React components.
- **Cross-platform** – Works seamlessly in modern browsers across devices.

---

## 🏗️ Tech Stack

- **Frontend**: React (Next.js 13)
- **Backend**: Node.js + Express
- **Real-time Messaging**: [GetStream.io (Stream Chat)](https://getstream.io)
- **Styling**: CSS + Stream Chat React UI components

---

## 🚀 Quick Start

1. **Clone the repo**
   ```bash
   git clone https://github.com/adrianhajdin/project_medical_pager_chat.git
   cd project_medical_pager_chat
   ```

2. **Install dependencies**
   ```bash
   cd client
   npm install

   cd ../server
   npm install
   ```

3. **Configure environment variables**  
   Create a `.env` in `server/` with:
   ```
   STREAM_API_KEY=your_stream_api_key
   STREAM_API_SECRET=your_stream_api_secret
   PORT=8000
   ```

4. **Start the development servers**
   ```bash
   # In one terminal:
   cd server && npm start

   # In another terminal:
   cd client && npm start
   ```
   - Backend runs on `http://localhost:8000`
   - Frontend runs on `http://localhost:3000`

---

## 🧩 Usage Guide

1. **Sign up / Log in** as a staff member (email + name).
2. **Create or select** existing chat channels (like "ER", "Radiology", etc.).
3. **Start chatting** with colleagues in real time.
4. **Enjoy instant updates** as messages stream live via GetStream.

---






