# Expense Tracker System

A full-stack expense management system with authentication, transaction tracking, reminders, and real-time insights.

## 🚀 Features

* User authentication and secure account management
* Add, update, and track expenses and transactions
* Real-time balance calculation and financial overview
* Email notifications and reminders
* Razorpay integration for payments
* Dashboard with insights and analytics

## 🛠️ Tech Stack

* **Frontend:** React, TypeScript, Vite, Tailwind CSS
* **Backend:** Node.js, Express
* **Database:** Supabase / MongoDB
* **Payments:** Razorpay
* **Other:** JWT Authentication, Email Services

## 📂 Project Structure

```id="b1"
backend/
  ├── routes/
  ├── models/
  ├── middleware/
  ├── utils/
  ├── server.js

frontend/
  ├── src/
  ├── public/
```

## ⚙️ Setup Instructions

### 1. Clone repository

```id="b2"
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Backend setup

```id="b3"
cd backend
npm install
node server.js
```

### 3. Frontend setup

```id="b4"
cd frontend
npm install
npm run dev
```

## 🔒 Environment Variables

Create a `.env` file:

```id="b5"
JWT_SECRET=your_secret
SUPABASE_URL=your_url
SUPABASE_ANON_KEY=your_key
RAZORPAY_KEY=your_key
```

## 📊 Highlights

* Built modular backend APIs for authentication, transactions, and reminders
* Designed database schemas for efficient transaction tracking
* Integrated payment and notification systems for real-world functionality

## 🚀 Future Improvements

* Add budgeting and spending analytics
* Improve UI/UX
* Deploy on cloud

---
