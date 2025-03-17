# Go Real-Time Chat - Scalable & Secure Messaging Application

🚀 **Go Real-Time Chat** is a **real-time messaging application** built with **Golang**, **WebSockets**, and **Next.js**. It provides a **scalable, secure, and efficient** chat platform for seamless communication.

## 📌 Features

✅ **Real-Time Messaging** – WebSocket-based instant chat 💬  
✅ **JWT Authentication** – Secure user sessions 🔐  
✅ **PostgreSQL for Storage** – Scalable database for chat rooms & messages 🗄️  
✅ **Dockerized Deployment** – Easy to set up and run in any environment 🐳  
✅ **Next.js & Tailwind UI** – Smooth and responsive frontend ⚡  

## ⚙️ Tech Stack

🔹 **Backend:** Golang (Gin, WebSockets), PostgreSQL, JWT, Docker  
🔹 **Frontend:** Next.js, TypeScript, TailwindCSS  
🔹 **Architecture:** REST API, WebSockets, Middleware for security  

## 📂 Project Structure
```
Go-RealTime-Chat/
│── server/
│   ├── cmd/
│   ├── db/
│   ├── internal/
│   │   ├── user/
│   │   ├── ws/
│   ├── router/
│   ├── util/
│   ├── main.go
│── frontend/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── styles/
│── docker-compose.yml
│── README.md
```

## 🚀 Getting Started

### Prerequisites
- Go 1.20+
- Node.js 18+
- PostgreSQL
- Docker (optional for containerized setup)

### Backend Setup
```sh
git clone [https://github.com/hbardhan/go-realtime-chat.git](https://github.com/hbardhan/Go-Real-Time-Chat---Scalable-Secure-Messaging-Application-)
cd go-realtime-chat/server
go mod tidy
go run main.go
```

### Frontend Setup
```sh
cd go-realtime-chat/frontend
npm install
npm run dev
```

## 🌍 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/signup` | User registration |
| POST | `/login` | User authentication |
| GET | `/logout` | User logout |
| POST | `/ws/createRoom` | Create chat room |
| GET | `/ws/joinRoom/:roomId` | Join a chat room |
| GET | `/ws/getRooms` | Fetch all rooms |
| GET | `/ws/getClients/:roomId` | Fetch clients in a room |

## 📡 WebSocket Events
| Event | Description |
|-------|------------|
| `message` | Send and receive messages |
| `join` | Join a chat room |
| `leave` | Leave a chat room |

## 💡 Future Enhancements
- 🔹 1-on-1 private messaging
- 📷 Media file sharing
- 🚀 Cloud deployment

## 📜 License
This project is licensed under the **MIT License**.

---
💬 **Let's connect!** Feel free to contribute, raise issues, or share feedback! 🙌  

