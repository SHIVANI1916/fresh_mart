# FreshMart — Premium Grocery E-Commerce 🛒

[![Project Status: Active](https://img.shields.io/badge/Project%20Status-Active-success.svg)](https://github.com/SHIVANI1916/fresh_mart)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)](https://github.com/SHIVANI1916/fresh_mart)

FreshMart is a high-performance, full-stack grocery application built with the **MERN stack**. It features a modern "Glassmorphism" aesthetic, real-time stock management, and a robust admin dashboard.

![FreshMart Banner](https://placehold.co/1200x400/22c55e/ffffff?text=FreshMart+Grocery+Platform)

---

# 🚀 Repository & Demo

- **GitHub Repository:** https://github.com/SHIVANI1916/fresh_mart
- **Live Demo:** https://freshmart-db6y.onrender.com/

---

# ✨ Key Features

## 👤 User Experience

- **Modern UI/UX:** Built with Tailwind CSS and "Outfit" typography for a premium feel.
- **Product Discovery:** Advanced filtering by category, price range, and search.
- **Shopping Cart:** Real-time updates, guest-cart support, and persistent state.
- **Secure Checkout:** Validated shipping forms and simulated payment processing.
- **Order Tracking:** Detailed order history and status updates.

## 🛡️ Security & Reliability

- **Firebase Authentication:** Google OAuth & Email/Password login with email verification.
- **JWT Authentication:** Secure API route protection synced with Firebase Admin SDK.
- **Stock Integrity:** Atomic stock deduction to prevent overselling.
- **API Protection:** Admin-only routes and middleware validation.
- **Production Ready:** Configured with Helmet, CORS, and structured logging.

## ⚡ Performance & Optimization

- **WebP Image Format:** Optimized product images for fast loading.
- **Smart Authentication:** Automatically attempts login if an account already exists.

## ⚙️ Admin Dashboard

- Inventory Management (CRUD)
- Order Management
- Analytics Dashboard
- Inventory Health Monitoring

---

# 🛠️ Tech Stack

## Frontend

- React 19
- Vite
- Tailwind CSS
- React Router 7

## Backend

- Node.js
- Express.js

## Database

- MongoDB
- Mongoose ODM

## Authentication

- Firebase Authentication
- Firebase Admin SDK
- JWT

## State Management

- React Context API

## Testing

- Vitest
- Jest
- Supertest
- Playwright

---

# 📦 Project Structure

```text
fresh_mart/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── services/
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   └── routes/
│
└── tests/
```

---

# 🔧 Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/SHIVANI1916/fresh_mart.git
cd fresh_mart
```

---

## 2. Backend Setup

```bash
cd server
npm install

# Create .env file based on .env.example
# Add MongoDB URI and Firebase credentials

npm run seed
npm run dev
```

---

## 3. Frontend Setup

```bash
cd ../client
npm install
npm run dev
```

---

## 4. Running Tests

```bash
# Backend
cd server
npm test

# Frontend
cd ../client
npm test

# End-to-End Tests
npx playwright test
```

---

# 📝 API Overview

| Method | Endpoint | Description | Authentication |
|---------|----------|-------------|----------------|
| POST | `/api/auth/login` | User Login | Public |
| GET | `/api/products` | Get All Products | Public |
| POST | `/api/orders` | Create Order | User |
| GET | `/api/admin/orders` | Get All Orders | Admin |

---

# 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for details.

---

# 👩‍💻 Author

**Bommera Shivani**

Electronics and Communication Engineering

Vardhaman College of Engineering

GitHub: https://github.com/SHIVANI1916

---

⭐ If you found this project helpful, please consider giving it a **star** on GitHub!
