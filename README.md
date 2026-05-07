# EduVault 🎓

EduVault is a full-stack Learning Management System (LMS) designed to simplify course management, assignment handling, communication, and academic integrity checks for both teachers and students.

The platform combines a modern React frontend with a powerful Node.js + Express backend and MongoDB database to deliver a seamless educational experience.

---

## 🚀 Features

### 🔐 Authentication & Profile Management
- Student & Teacher Signup/Login
- Google Authentication
- JWT-based Authentication
- Password Reset System
- Profile Photo Upload
- Account Settings Management

### 📚 Courses & Enrollment
- Teacher Course Creation & Management
- Student Course Browsing
- Enrollment Requests
- Enrollment Approval/Rejection
- Course Analytics Dashboard

### 📝 Assignments & Submissions
- Assignment Creation, Update & Deletion
- File Upload Submission Support
- Submission History
- Teacher Review Workflow
- Assignment Analytics

### 🧠 Detection Tools
- AI-Generated Content Detection
- Plagiarism Checking
- Text Analysis Utilities

### 💬 Chat & Notifications
- Real-Time Teacher-Student Communication
- Chat History
- Notification Delivery
- Read Status Tracking
- Notification History

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React, React Router, Axios, Framer Motion, React Toastify, Recharts |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, Google Sign-In |
| File Handling | Multer, Mammoth, pdf-parse |
| Notifications & Email | Nodemailer |

---

# 📁 Project Structure

```bash
capstoneProject_final/
├── backend/
│   ├── server.js
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── utils/
│
└── frontend/
    ├── src/
    ├── public/
    └── build/
```

---

# 🌐 Backend API Routes

```bash
/api/auth
/api/courses
/api/assignments
/api/submissions
/api/notifications
/api/enrollment
/api/detection
/api/chat
```

✅ Health Check Endpoint:

```bash
/api/health
```

---

# ⚙️ Prerequisites

Make sure you have installed:

- Node.js (v18 or later)
- npm
- MongoDB Database

---

# 🔑 Environment Variables

Create a `.env` file inside the `backend/` folder.

```env
PORT=5000
NODE_ENV=development
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=30d

FRONTEND_URL=http://localhost:3000

GOOGLE_CLIENT_ID=your_google_client_id

HUGGINGFACE_API_KEY=your_huggingface_api_key

SMTP_HOST=your_smtp_host
SMTP_PORT=587
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password

FROM_EMAIL=your_sender_email
EMAIL_USE_TEACHER_FROM=false
```

---

# 📦 Installation

## 1️⃣ Clone the Repository

```bash
git clone <your-repository-url>
cd capstoneProject_final
```

---

## 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

---

## 3️⃣ Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

# ▶️ Running the Project

## Start Backend Server

```bash
cd backend
npm run dev
```

Backend runs on:

```bash
http://localhost:5000
```

---

## Start Frontend Server

```bash
cd frontend
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 🏗️ Production Build

Build frontend for production:

```bash
cd frontend
npm run build
```

---


# 🎯 Project Objective

EduVault aims to provide a centralized platform for:
- Digital learning management
- Assignment workflow automation
- Student-teacher communication
- Academic integrity monitoring
- Analytics-driven education management

---

# 📄 License

No license has been specified yet.

Add a license if you plan to make the project public or reusable.

---


⭐ If you like this project, consider giving it a star on GitHub!
