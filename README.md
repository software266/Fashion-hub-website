# Fashion Hub - E-Commerce Platform

A full-stack fashion e-commerce web application for online shopping with product management, orders, payments, reviews, and admin dashboard.

## 📌 Project Overview

Fashion Hub is a modern fashion retail platform that provides users a smooth shopping experience and helps admins manage products, users, orders, payments, and reports.

## 🚀 Features

### 👤 User Features
- User registration & login with JWT authentication
- Browse products by category
- Search and filter products
- Add to cart & wishlist
- Place orders (UPI/COD)
- Track order status
- Product reviews & ratings
- Profile management
- Custom tailoring appointment booking

### 🛠️ Admin Features
- Admin dashboard with analytics
- Product CRUD operations
- Manage users
- Manage orders & payments
- Verify UPI payments
- Manage reviews & appointments
- Export reports to PDF

## 🛠️ Technology Stack

**Frontend:**
- React.js
- CSS3
- Axios

**Backend:**
- Node.js
- Express.js

**Database:**
- MySQL

**Other:**
- JWT Authentication
- Nodemailer
- PDF Export

## 📂 Project Structure
Fashion-Hub/
│
├── backend/
│ ├── controllers/
│ ├── routes/
│ ├── middleware/
│ ├── services/
│ ├── database.sql
│ └── server.js
│
├── frontend/
│ ├── src/
│ ├── components/
│ ├── styles/
│ └── App.jsx
│
└── README.md

## ⚙️ Installation & Setup

### Backend
```bash
cd backend
npm install

Create .env file:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=fashion_hub
PORT=5000
JWT_SECRET=your_secret_key

Run backend:
node server.js
Frontend
cd frontend
npm install
npm run dev

Frontend runs on:
http://localhost:5173

Backend runs on:
http://localhost:5000
🗄️ Database Tables

Main tables:
Users
Products
Orders
Reviews
Appointments

🔐 Security
JWT authentication
Password hashing
Role-based access (Admin/User)
Protected API routes
Data validation

📊 Project Highlights
Full-stack e-commerce application
Responsive user interface
Admin management system
Order & payment management
Review and appointment system
PDF report generation

👩‍💻 Project Details
Project Type: Full Stack Web Application
Domain: Fashion & Retail
Year: 2025

📄 License
Educational purpose project.
