# 💬 Live Chat Application

A full-stack real-time chat app with **Node.js/Express** backend and **React/Vite + TailwindCSS** frontend, supporting authentication and live messaging via **Socket.IO**.

---

## ⚙️ Setup

```bash
# Clone repo
git
cd 

# Install client dependencies
cd live-chat-client
npm install    # or bun install

# Install server dependencies
cd ../live-chat-server
npm install    # or bun install

🚀 Run
Start Server
cd live-chat-server
npm start      # or npm run dev


Runs on 👉 http://localhost:5000 (check .env).

Start Client
cd live-chat-client
npm run dev


Runs on 👉 http://localhost:5173 (Vite) or http://localhost:3000 (CRA).

📂 Structure

live-chat-client/ → frontend (React/Vite, Tailwind)

live-chat-server/ → backend (Node.js, Express, MongoDB, Socket.IO)

.env (server) → contains PORT, MONGO_URI, JWT_SECRET

📦 Build
# Client production build
cd live-chat-client
npm run build   # outputs to dist/

# Run backend
cd ../live-chat-server
node index.js

📝 Notes

Client ↔ Server API base URL: http://localhost:5000

TailwindCSS preconfigured in frontend

Real-time messaging powered by Socket.IO
