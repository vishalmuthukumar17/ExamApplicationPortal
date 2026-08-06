# 📝 Exam Application Portal - Wireframe

> High-fidelity wireframe prototype for a modern online examination system

![Version](https://img.shields.io/badge/version-2.0.0-blue) ![Status](https://img.shields.io/badge/status-completed-success) ![Tool](https://img.shields.io/badge/tool-Figma-purple) ![License](https://img.shields.io/badge/license-MIT-green)

---

## 📋 Description

A complete high-fidelity wireframe prototype for an online examination portal featuring student registration, exam browsing, real-time testing with timer, payment integration, and admin dashboards for managing exams, users, and results. Designed with a comprehensive design system and responsive layouts.

---

## ✨ Features

**Students:** Registration & Login | Dashboard | Exam Interface with Timer | Results & Performance | Payment Gateway | Profile Management

**Admins:** Analytics Dashboard | Exam Creation | Question Bank Management | User Management | Result Publishing | Reports Generation

---

## 🖥️ Screens

Landing Page | Login/Signup | Student Dashboard | Exam Listing | Exam Interface | Results Page | Admin Dashboard | Exam Creation | User Management 

---

## 🎨 Design System

| Element | Details |
|---------|---------|
| Primary Color | `#2563EB` |
| Typography | Inter / Poppins |
| Components | Buttons, Cards, Modals, Tables, Timers |
| Responsive | Mobile, Tablet, Desktop |

---

## 🔄 User Flow

```
Landing → Login/Signup → Dashboard → Select Exam → Start Exam → Submit → View Results
                                      ↓
Admin Login → Admin Dashboard → Manage Exams/Users/Reports
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Figma | Wireframing & Prototyping |
| React.js / Next.js | Frontend |
| Node.js / Django | Backend |
| PostgreSQL / MongoDB | Database |

---

## 📁 Folder Structure

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
├── .gitignore
└── README.md
```

---

## 🚀 Quick Start

# Clone repository
```bash
git clone https://github.com/vishalmuthukumar17/ExamApplicationPortal.git

```

---

## 📊 Project Status

| Phase | Status |
|-------|--------|
| Low-Fidelity Wireframes | ✅ |
| High-Fidelity Design | ✅ |
| Interactive Prototype | ✅ |
| Usability Testing | ✅ |
| Development Handoff | ✅ |

---

## 🤝 Contributing

1. Fork the repo
2. Create feature branch (`git checkout -b feature/amazing`)
3. Commit changes
4. Push to branch
5. Open Pull Request

---

