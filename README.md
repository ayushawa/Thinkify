# Thinkify

Thinkify is a full-stack MERN application for managing posts, products, and tasks through a secure role-based dashboard built with React, Node.js, Express, and MongoDB.

---

## Preview

<p align="center">
  <img src="preview.png" alt="Thinkify Preview" width="900"/>
</p>

---

# Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

---

# Features

## Authentication

* User Registration
* Secure Login
* JWT Authentication
* Role-Based Authorization
* Password Encryption

## User Dashboard

* User Profile
* Account Settings
* Change Password
* Sign Out

## Admin Dashboard

* User Management
* Role Distribution Analytics
* Monthly User Activity

## Posts

* Create Post
* View Posts
* Manage Personal Posts

## Marketplace

* Add Products
* Manage Products
* Product Listings

## Task Management

* Create Tasks
* Update Task Status
* Organize Daily Activities

---

# Project Structure

```text
Thinkify
│
├── client
│   ├── components
│   ├── pages
│   ├── layouts
│   ├── routes
│   └── src
│
├── server
│   ├── config
│   ├── controller
│   ├── middleware
│   ├── models
│   ├── routes
│   └── uploads
│
└── README.md
```

---

# Live Demo

### Frontend

https://thinkify-two.vercel.app

### Backend API

https://thinkify-backend-hw9s.onrender.com

> **Note:** The backend is hosted on Render's free tier. The first request after inactivity may take around 30–60 seconds while the service wakes up.

---

# Getting Started

## Prerequisites

* Node.js
* MongoDB

---

# Installation

```bash
git clone https://github.com/ayushawa/Thinkify.git
```

### Backend

```bash
cd server
npm install
npx nodemon index.js
```

### Frontend

```bash
cd ../client
npm install
npm run dev
```

---

# Environment Variables

## Backend (.env)

```env
PORT=3000
DATABASE_URL=your_database_url
DATABASE_NAME=thinkify
JWT_SECRET_KEY=your_secret_key
COOKIE_KEY=thinkify
COOKIE_EXPIRES=5d
BCRYPT_GEN_SALT_NUMBER=10
UPLOAD_DIRECTORY=uploads
```

## Frontend (.env)

```env
VITE_SERVER_ENDPOINT=your_backend_api
VITE_TOKEN_KEY=thinkify
VITE_USER_ROLE=role
VITE_COOKIE_EXPIRES=1
```

---

# Future Improvements

* Real-time notifications using WebSockets
* Email verification and password reset
* Product search and advanced filtering
* User profile image uploads
* Dark mode
* Pagination and infinite scrolling
* Docker support
* CI/CD pipeline with GitHub Actions
* Unit and integration testing
* Performance optimization and caching

---

# License

This project is developed for educational and portfolio purposes.

---

## Author

**Ayush Awasthi**

If you found this project helpful, consider giving it a ⭐ on GitHub.
