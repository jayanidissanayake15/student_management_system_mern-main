# 🎓 Student Management System (MERN + TypeScript)

A modern **Student Management System / Learning Management System (LMS)** built using the **MERN Stack (MongoDB, Express, React, Node.js)** with **TypeScript**, designed for scalable academic management and automation.

---

## 🚀 Key Features

* 🔐 Secure Authentication & Authorization (JWT)
* 👨‍🎓 Student Management System
* 📚 Academic & Course Management
* 📝 Assignment Management System
* 🤖 AI-Powered Features (Google Generative AI)
* 📢 Notice & Announcement System
* 📊 Reports Generation
* 📄 PDF Export (Reports & Data)
* 📈 Excel Export Support
* ☁️ Cloudinary File Upload Integration
* 📧 Email Notification System (Nodemailer)
* 🔄 Real-time Communication (Socket.IO)
* 🛡️ Security Middleware (Helmet, CORS)
* 📦 RESTful API Architecture

---

## 🛠️ Tech Stack

### Frontend

* React 19
* TypeScript
* Vite
* Tailwind CSS
* Redux Toolkit
* React Router
* React Hook Form
* Zod Validation
* Axios
* Recharts
* Framer Motion
* Socket.IO Client

### Backend

* Node.js
* Express.js
* TypeScript
* MongoDB + Mongoose
* JWT Authentication
* bcryptjs
* Nodemailer
* Multer
* Cloudinary
* Socket.IO
* PDFKit
* ExcelJS
* Google Generative AI

---

## 📁 Project Structure

```text
student_management_system_mern-main/
│
├── backend/
│   ├── src/
│   ├── package.json
│   └── Dockerfile
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── Dockerfile
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in backend root:

```env
PORT=5003
MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

EMAIL_USER=your_email@gmail.com
EMAIL_PASSWORD=your_app_password

GOOGLE_API_KEY=your_google_ai_api_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 API Endpoints

| Endpoint         | Description           |
| ---------------- | --------------------- |
| /api/auth        | Authentication        |
| /api/academic    | Academic Management   |
| /api/assignments | Assignment Management |
| /api/ai          | AI Services           |
| /api/reports     | Reports Generation    |
| /api/notices     | Notice Management     |
| /health          | Server Health Check   |

---

## 🐳 Docker Support

### Build Images

```bash
docker build -t sms-backend ./backend
docker build -t sms-frontend ./frontend
```

---

## 🔒 Security Features

* JWT Authentication
* Password Hashing (bcryptjs)
* Helmet Security Headers
* CORS Protection
* Input Validation (Zod)

---

## 📈 Future Improvements

* Attendance Tracking System
* Online Examination Module
* Payment Gateway Integration
* Mobile Application (React Native)
* Advanced Analytics Dashboard

---

## 👨‍💻 Developer Info

This project is a **full-stack MERN LMS system** built for educational management, scalability, and real-world deployment scenarios.

---

## 📜 License

This project is licensed under the MIT License.

---

# 🔥 Improvements I Made

* More professional wording
* Cleaner structure
* Better headings hierarchy
* Consistent formatting
* More “GitHub-ready” look
* Clear separation of sections
* Improved readability for recruiters


