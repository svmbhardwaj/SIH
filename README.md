# 🚆 Train Traffic Optimization System – SIH 2025

> A full-stack solution for **Smart India Hackathon 2025** to make railway traffic smarter, faster, and more reliable.  
> Built with ❤️ by our team, combining **modern web technologies** with **real-world railway challenges**.

---

## 🌐 Live Demo
👉 [Frontend Live on Vercel](https://sih-frontend-qfappvai8-arnab-maitys-projects-20d97419.vercel.app)

---

## 📖 Project Overview
Railway traffic in India is massive and complex — thousands of trains run daily, facing issues like delays, route conflicts, and unpredictable congestion.  

Our project is a **Train Traffic Optimization System** that tackles these problems through:
- **Real-time train tracking** with live updates  
- **Smart route optimization** to reduce conflicts  
- **Schedule management** with easy CRUD operations  
- **Analytics dashboard** for insights and decision-making  

In short, this system is designed to **help railway operators manage traffic efficiently** while also providing an **intuitive interface** for monitoring.

---

## ✨ Key Features
- 🔴 **Real-time Train Monitoring** – Track active trains and their status.  
- 🛤️ **Route Optimization** – Conflict resolution and shortest-path suggestions.  
- 📅 **Schedule Management** – Add, edit, or remove train schedules.  
- 📊 **Analytics Dashboard** – Get performance stats and trends.  
- 🌙 **Modern & Responsive UI** – Clean railway-themed interface.  

---

## 🛠️ Tech Stack

### 🔹 Frontend
- **Next.js + TypeScript** – Modern React framework with type safety  
- **Tailwind CSS** – Fast and responsive styling  
- **Axios** – API communication with backend  
- **Socket.io Client** – Live updates directly on the dashboard  

### 🔹 Backend
- **Node.js + Express.js** – REST APIs and core backend logic  
- **Socket.io Server** – Real-time data streaming between trains and dashboard  
- **Mongoose** – ODM for MongoDB models  
- **Express Validator** – Input validation and secure data handling  
- **Helmet & dotenv** – Security and environment configuration  

### 🔹 Database
- **MongoDB (Atlas/Local)** – Stores train details, schedules, routes, and analytics  
- **Collections** include:
  - `Trains` → train ID, route, live status  
  - `Schedules` → timetables, delays, reschedules  
  - `Optimization` → route conflict resolutions & history  
  - `Analytics` → performance metrics, delay stats  

---

## 📂 Project Structure
```
SIH/
│── frontend/        # Next.js application (UI/UX)
│   ├── app/         # Pages & routing
│   ├── components/  # Reusable React components
│   ├── services/    # API calls
│   └── types/       # TypeScript types

│── backend/         # Node.js Express API server
│   ├── models/      # Mongoose schemas
│   ├── routes/      # API routes
│   ├── middleware/  # Validation & security
│   └── server.js    # App entry point

│── .github/         # GitHub workflows
│── README.md        # Project documentation
└── package.json     # Dependencies & scripts
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/arnab-maity007/SIH.git
cd SIH
```

### 2. Install Dependencies
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

### 3. Setup Environment Variables
Create a `.env` file in `/backend`:
```env
PORT=5001
MONGODB_URI=mongodb://localhost:27017/train_optimization
JWT_SECRET=your_secret_key
NODE_ENV=development
```

### 4. Run Development Servers
```bash
# Backend (http://localhost:5001)
cd backend
npm run dev

# Frontend (http://localhost:3000)
cd frontend
npm run dev
```

---

## 👥 Team Credits
This project is the result of teamwork, countless discussions, debugging sessions, and a lot of chai ☕.  
We are proud to present this as our **SIH 2025 solution**.  

- **Frontend Development**  
  - [Arnab Maity](https://github.com/arnab-maity007)  
  - [Shivam Bhardwaj](https://github.com/svmbhardwaj)  

- **Backend Development**  
  - [Divyansh Shukla](https://github.com/Divyanshhhhhhh-creator)  
  - [Arnab Maity](https://github.com/arnab-maity007)  

---

## 📄 License
This project was created for **Smart India Hackathon 2025**.   

---

**Built with ❤️, teamwork, and innovation for SIH 2025**  
*“Transforming Indian Railways through Technology”*
