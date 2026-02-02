# 🧑‍💼 Jobby – Job Portal System

Jobby is a full-stack web-based Job Portal application designed to connect job seekers with recruiters on a single platform. The system allows users to search and apply for jobs, upload resumes, and track applications, while admins can manage job postings, users, and applications efficiently.

---

## 📌 Project Overview

The Job Portal System simulates a real-world recruitment platform with secure authentication, job management, resume uploads, and admin control. It is built using modern web technologies with a focus on clean UI, scalability, and real-time data handling.

---

## ✨ Key Features

- User registration and login  
- OTP-based authentication  
- Job posting and job search  
- Resume upload and application tracking  
- Admin panel for managing jobs and users  
- Blog and contact modules  
- Secure REST API integration  

---

## 🛠 Technology Stack

### Frontend
- HTML  
- CSS  
- JavaScript  
- React.js  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  

### Tools & Libraries
- Git & GitHub  
- VS Code  
- Postman  
- Multer (file upload)  
- JWT (authentication)  

---

## 🏗 System Architecture

The application follows a client–server architecture:

- Frontend communicates with backend using REST APIs  
- Backend handles authentication, business logic, and database operations  
- MongoDB stores users, jobs, applications, and resume data  

---

## ⚙️ Backend Structure

- `server.js` – Application entry point  
- `controllers/` – Business logic (auth, jobs, users, applications)  
- `models/` – MongoDB schemas  
- `middleware/` – Authentication and file upload handling  
- `routes/` – API endpoints  

---

## 🎨 Frontend Structure

- Pages: Login, Register, Jobs, Apply, Admin  
- Reusable UI components  
- API integration using fetch/axios  
- Responsive and user-friendly design  

---

## 🔐 Security & Performance

- Password hashing  
- JWT-based authentication  
- OTP verification  
- Input validation on frontend and backend  
- Secure resume uploads  

---

## 🚀 How to Run the Project Locally

### ✅ Prerequisites
Make sure you have installed:
- Node.js (v16+ recommended)
- npm
- MongoDB (local or MongoDB Atlas)
- Git

---

### ▶️ Backend Setup

```bash
cd jobportal-backend
npm install
