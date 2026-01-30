# AngularEcommerce
ShopSphere is a full-stack e-commerce web application built with Angular 19, Tailwind CSS, Node.js, Express, and MySQL. It supports role-based authentication (User &amp; Admin), product management, cart, orders, and an admin dashboard with a clean, responsive UI.


# 🛍️ ShopSphere – Full Stack E-Commerce Application

ShopSphere is a modern **full-stack e-commerce web application** built using  
**Angular 19**, **Tailwind CSS**, **Node.js (Express)**, and **MySQL**.

The project supports **role-based authentication (User & Admin)** and includes
real-world e-commerce features like product listing, cart, orders, and an admin dashboard.

---

## 🚀 Tech Stack

### Frontend
- Angular 19 (Standalone Components)
- Tailwind CSS
- Angular Router
- RxJS
- JWT based authentication

### Backend
- Node.js
- Express.js
- MySQL
- JWT Authentication
- REST APIs

---

## 👥 User Roles & Features

### 🔓 Public (Without Login)
- Landing page
- Login & Signup pages

### 👤 User
- Login / Logout
- Product listing with images
- Add to cart
- View cart
- Place orders
- View **My Orders**
- Greeting message based on time (Good Morning / Afternoon / Evening / Night)

### 🛠️ Admin
- Admin dashboard
- View all orders
- View users summary (derived from orders)
- Admin orders management page

---

## 📦 Core Features

- Role based routing (User / Admin)
- Secure JWT authentication
- Responsive UI with Tailwind CSS
- Real-time cart count
- Orders management
- Clean and modular code structure
- Production-ready project structure

---

## 🗂️ Project Structure



frontend (Angular)
│
├── app
│ ├── admin
│ ├── user
│ ├── auth
│ ├── layouts
│ ├── core (services, guards)
│ └── pages
│
backend (Node + Express)
│
├── routes
├── controllers
├── middlewares
├── config
└── app.js




---

## ⚙️ Setup Instructions

### 1️⃣ Backend Setup
```bash
cd backend
npm install
npm start




cd frontend
npm install
ng serve




PORT=3000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=ecommerce
JWT_SECRET=your_secret_key
