# Online Course Platform

## 📖 Overview

Online Course Platform is a full-stack MERN application designed for modern e-learning. The platform allows students to browse courses, enroll in free or paid courses, track learning progress, and access lessons online. Administrators can manage courses, modules, lessons, users, enrollments, and platform revenue through a dedicated admin dashboard.

The application includes secure JWT authentication, role-based access control, Razorpay payment integration, email verification, password recovery, and progress tracking.

---

## 🚀 Features

### Student Features

* User Registration and Login
* JWT Authentication
* Email Verification
* Forgot Password & Reset Password
* Browse and Search Courses
* Course Enrollment
* Razorpay Payment Gateway Integration
* Video Lesson Playback
* Progress Tracking
* My Courses Dashboard

### Admin Features

* Admin Dashboard
* Course Management (Create, Update, Delete)
* Module and Lesson Management
* User Management
* Enrollment Management
* Revenue Tracking Dashboard
* Thumbnail Upload Support

---

## 🛠️ Tech Stack

### Frontend

* React.js (Vite)
* React Router
* Axios
* Context API
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Token)
* Role-Based Authorization

### Third-Party Services

* Razorpay Payment Gateway
* Nodemailer Email Service

---

## 📂 Project Structure

```bash
online-course-platform/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── scripts/
│   ├── uploads/
│   ├── utils/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── context/
│   │   ├── layouts/
│   │   ├── pages/
│   │   └── utils/
│   └── package.json
│
├── API_DOCUMENTATION.md
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/online-course-platform.git
cd online-course-platform
```

### Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```env
MONGODB_URI=mongodb://localhost:27017/project3
JWT_SECRET=your_secret_key
EMAIL_USER=your@gmail.com
EMAIL_PASS=your_app_password
EMAIL_FROM=Course Platform <your@gmail.com>
RAZORPAY_KEY_ID=rzp_test_xxxxx
RAZORPAY_KEY_SECRET=your_secret
CLIENT_URL=http://localhost:5173
```

### Frontend Setup

```bash
cd frontend
npm install
```

Create `.env` file:

```env
VITE_API_URL=http://localhost:5001/api
VITE_RAZORPAY_KEY_ID=rzp_test_xxxxx
```

---

## ▶️ Run Application

### Start Backend

```bash
cd backend
npm run dev
```

### Start Frontend

```bash
cd frontend
npm run dev
```

Frontend URL:

```text
http://localhost:5173
```

Backend API:

```text
http://localhost:5001/api
```

---

## 🗄️ Database Collections

* Users
* Courses
* Modules
* Lessons
* Enrollments
* Progresses
* Payments

---

## 💳 Payment Integration

The platform uses Razorpay Test Mode for secure online payments.

### Test Card

```text
Card Number: 4111 1111 1111 1111
Expiry: Any Future Date
CVV: Any 3 Digits
```

---

## 📧 Email Services

Nodemailer is used for:

* Email Verification
* Password Reset Emails
* Notification Emails

---

## 🔐 Security Features

* JWT Authentication
* Password Hashing
* Protected Routes
* Role-Based Access Control
* Environment Variable Protection

---

## 🔮 Future Enhancements

* Course Certificates
* Quiz & Assessment Module
* Live Classes
* Student Discussion Forum
* Course Reviews & Ratings
* Instructor Dashboard
* Multi-Language Support

---

## 👨‍💻 Author

Krishan Patel

* MERN Stack Developer
* GitHub: https://github.com/Krishan1155
