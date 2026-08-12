# 📝 Exam Application Portal

> A full-stack exam management system with student and admin interfaces

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Status](https://img.shields.io/badge/status-active-success)
![Frontend](https://img.shields.io/badge/frontend-React-61DAFB)
![Backend](https://img.shields.io/badge/backend-Node.js-339933)
![Database](https://img.shields.io/badge/database-MongoDB-47A248)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📋 Description

A complete exam application portal featuring student registration, real-time exam interface with timer, payment integration, and admin dashboards for managing exams, users, and results with responsive design.

---

## ✨ Features

**Students:** Registration & Login | Dashboard | Exam Interface with Timer | Results & Performance | Payment Gateway | Profile Management

**Admins:** Analytics Dashboard | Exam Creation | Question Bank Management | User Management | Result Publishing | Reports Generation

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | React.js / Next.js |
| Backend | Node.js / Express |
| Database | MongoDB / PostgreSQL |
| Authentication | JWT |
| Payment | Stripe / Razorpay |
| Design | Figma |

---

## 📁 Project Structure

```
exam-portal/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── auth/
│   │   │   │   ├── Login.jsx
│   │   │   │   └── Register.jsx
│   │   │   ├── student/
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── ExamInterface.jsx
│   │   │   │   └── Results.jsx
│   │   │   └── admin/
│   │   │       ├── AdminDashboard.jsx
│   │   │       ├── CreateExam.jsx
│   │   │       └── UserManagement.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   └── Payment.jsx
│   │   ├── styles/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── index.js
│   ├── public/
│   ├── package.json
│   └── .env
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── authController.js
│   │   │   ├── examController.js
│   │   │   └── userController.js
│   │   ├── models/
│   │   │   ├── User.js
│   │   │   ├── Exam.js
│   │   │   ├── Question.js
│   │   │   └── Result.js
│   │   ├── routes/
│   │   │   ├── authRoutes.js
│   │   │   ├── examRoutes.js
│   │   │   └── userRoutes.js
│   │   ├── middleware/
│   │   │   └── auth.js
│   │   └── config/
│   │       ├── database.js
│   │       └── passport.js
│   ├── package.json
│   └── .env
├── database/
│   ├── migrations/
│   └── seeders/
├── docker-compose.yml
└── README.md
```

---

## 🚀 Quick Start

### Frontend

```bash
cd frontend
npm install
npm start
```

### Backend

```bash
cd backend
npm install
npm run dev
```

### Environment Variables

Create `.env` files in both frontend and backend directories with required configurations.

---

## 📊 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | User registration |
| POST | `/api/auth/login` | User login |
| GET | `/api/exams` | Get all exams |
| POST | `/api/exams/create` | Create exam (admin) |
| POST | `/api/exams/submit` | Submit exam |
| GET | `/api/results/:id` | Get exam results |
| GET | `/api/admin/users` | Get all users (admin) |

---

## 📊 Project Status

| Phase | Status |
|-------|--------|
| Database Design | ✅ |
| Backend API | ✅ |
| Frontend UI | ✅ |
| Deployment | ✅ |

---

## 🤝 Contributing

1. Fork the repo
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open Pull Request

---

## 📝 License

MIT License

---


⭐ Star if helpful!

</div>
