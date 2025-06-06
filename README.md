# 📝 Task Management System

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) application designed to help individuals and teams manage their tasks effectively. Add, track, and complete tasks with a clean UI and powerful backend support.

---

## 🚀 Live Demo

🚧 **Live Demo Coming Soon...**

---

## 🛠️ Features

- ✅ Create, edit, and delete tasks
- 🗓️ Set due dates and priorities
- 📂 Organize tasks by status (Pending / Completed)
- 🔍 Filter & search tasks
- 🧑‍💻 User authentication (Login & Registration)
- 🔐 JWT-based secure API endpoints
- 🌐 Fully responsive UI

---

## 🧱 Tech Stack

**Frontend:**
- React.js
- Redux Toolkit (for state management)
- Tailwind CSS (for styling)
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication

---

## ⚙️ Installation & Setup

### 1. Clone the repo

```
git clone https://github.com/dLomas26/Task-Management-System.git
cd Task-Management-System
```

### 2. Backend Setup

```
cd backend
npm install
```

Create a .env file inside /backend:

```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

Start the backend server:

```
npm run server
```

### 3. Frontend Setup

```
cd ../frontend
npm install
```

Create a .env file inside /frontend:

```
VITE_API_URL=http://localhost:5000
```

Start the frontend dev server:

```
npm run dev
