# 🌾 AgroSmart — Crop Advisory & Farm Management System

AgroSmart is a full stack web application that helps farmers make smarter decisions.
Get tailored crop recommendations based on soil type and season, manage daily farm
tasks, and stay updated with seasonal weather tips — all in one place.

🔗 **Live Demo:** [Open on Replit](https://replit.com/@ramyaeeru9/Agro-Smart-Cro)

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](assets/screenshots/home.png)

> Smart Farming Starts Here — with quick access to Crop Advisor and Task Tracker.

---

### 🌱 Crop Advisor
![Crop Advisor](assets/screenshots/crop-advisor.png)

> Select soil type and season to get tailored crop planting recommendations.
> The database has 14 crops registered across Kharif, Rabi, and Zaid seasons.

---

### ✅ Farm Tasks
![Farm Tasks](assets/screenshots/farm-tasks.png)

> Add, manage, and track your daily farm chores with due dates and completion status.

---

### 🌤️ Weather & Seasonal Tips
![Weather Tips](assets/screenshots/weather-tips.png)

> Practical seasonal advice for Kharif, Rabi, and Zaid seasons to protect crops
> and maximize yield.

---

## ✨ Features

- 🌿 **Crop Advisor** — Get crop recommendations based on soil type (Black, Loamy, Sandy) and season (Kharif, Rabi, Zaid)
- ✅ **Farm Task Tracker** — Add, delete, and mark tasks as done with due dates
- 🌤️ **Weather Tips** — Season-wise practical advice for better farming decisions
- 🔐 **User Authentication** — Register and login to save your personal data
- 📊 **Database Summary** — See total crops registered by season and soil type

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | TypeScript, HTML, CSS |
| Backend | Node.js + Express 5 |
| Database | PostgreSQL + Drizzle ORM |
| Validation | Zod |
| Language | TypeScript 5.9 |
| Package Manager | pnpm (workspaces) |

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js 24+
- pnpm → `npm install -g pnpm`
- PostgreSQL running locally

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/ramya-021/Agro-Smart-Cro.git

# 2. Navigate into project
cd Agro-Smart-Cro

# 3. Install dependencies
pnpm install

# 4. Create .env file and add your database URL
DATABASE_URL=postgresql://username:password@localhost:5432/agrosmart

# 5. Push database schema
pnpm --filter @workspace/db run push

# 6. Start the backend server
pnpm --filter @workspace/api-server run dev
```

---

## 📁 Project Structure
