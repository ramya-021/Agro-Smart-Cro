# 🌾 AgroSmart-Cro — Crop Advisory & Farm Management System

A full stack web application that helps farmers get smart crop recommendations
and manage their farm tasks efficiently.

---

## 🚀 Live Demo
> [Open on Replit](https://replit.com/@ramyaeeru9/Agro-Smart-Cro)

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](assets/screenshots/home.png)

### 🌱 Crop Advisor
![Crop Advisor](assets/screenshots/crop-advisor.png)

### ✅ Task Tracker
![Task Tracker](assets/screenshots/task-tracker.png)

---

## 🧰 Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Frontend   | TypeScript, HTML, CSS   |
| Backend    | Node.js + Express 5     |
| Database   | PostgreSQL + Drizzle ORM|
| Validation | Zod                     |
| Language   | TypeScript 5.9          |
| Package Manager | pnpm (workspaces) |

---

## ✨ Features

- 🌿 Crop recommendations based on soil type and season
- ✅ Farm task tracker (Add, Update, Delete, Mark Done)
- 🔐 User authentication (Register & Login)
- 📊 Dashboard with farm overview
- 📱 Fully responsive design

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js 24+
- pnpm installed (`npm install -g pnpm`)
- PostgreSQL running locally

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/ramya-021/Agro-Smart-Cro.git

# 2. Go into the project folder
cd Agro-Smart-Cro

# 3. Install all dependencies
pnpm install

# 4. Set your database URL in .env file
DATABASE_URL=postgresql://username:password@localhost:5432/agrosmart

# 5. Push the database schema
pnpm --filter @workspace/db run push

# 6. Start the backend server
pnpm --filter @workspace/api-server run dev
```

---

## 📁 Project Structure
