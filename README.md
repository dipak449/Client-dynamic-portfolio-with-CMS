# 🥋 Taekwondo Referee Portfolio with CMS

A full-stack MERN (MongoDB, Express, React, Node.js) web application built for a professional International Taekwondo Referee.  
This platform includes a dynamic public portfolio website and a secure Admin CMS panel to manage all content easily.

---

## 🌟 Project Overview

This project is designed to provide:

- A modern public portfolio website
- A dynamic content management system (CMS)
- Secure admin authentication
- Image uploads with Cloudinary
- Fully responsive and animated UI

---

## 🚀 Features

### 🌐 Public Website

- Premium Hero Carousel (Auto Sliding)
- About Section (Dynamic from Database)
- Certifications Section
- Events Section
- Featured Gallery with Lightbox View
- Latest Updates Section
- Contact Form
- Smooth Animations using Framer Motion
- Responsive Design

---

### 🔐 Admin CMS Panel

- Secure Admin Setup
- Admin Login (JWT Authentication)
- Dashboard Overview
- Create / Edit / Delete Posts
- Manage Events
- Manage Certifications
- Manage Gallery Images (Cloudinary Integration)
- View Contact Messages (Admin Inbox)

---

## 🛠️ Tech Stack

### Frontend
- React (Create React App)
- React Router
- Axios
- Framer Motion
- Modern CSS / Theme Styling

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cloudinary (Image Hosting)

---

## 📂 Project Structure


backend/
└── src/
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
└── server.js

frontend/
└── src/
├── components/
├── layout/
├── pages/
├── routes/
├── services/
└── theme/


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository


git clone https://github.com/dipak449/Client-dynamic-portfolio-with-CMS.git


---

### 2️⃣ Backend Setup


cd backend
npm install
npm run dev


Create a `.env` file inside the backend folder and add:


PORT=
MONGO_URI=
JWT_SECRET=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=


---

### 3️⃣ Frontend Setup


cd frontend
npm install
npm start


Frontend runs on:

http://localhost:3000


Backend runs on:

http://localhost:8000


---

## 🔐 Admin API Routes

- POST `/admin/setup`
- POST `/admin/login`
- GET `/admin/me`

---

## 📈 Future Improvements

- Role-based access control
- SEO optimization
- Production deployment (Render + Vercel)
- Performance optimization
- Blog comments system

---

## 👨‍💻 Developed By

**Dipak Kumar Sah**  
B.Tech – Computer Science & Engineering  
Full Stack MERN Developer  
India 🇮🇳

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!