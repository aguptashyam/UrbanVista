<h1 align="center">UrbanVista – Modern Minimal Fashion E-Commerce Platform</h1>

UrbanVista is a full-stack e-commerce web application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The platform delivers a clean, modern shopping experience focused on minimal fashion, combined with a robust backend for secure transactions and efficient administration.

---

## Project Overview

UrbanVista allows users to browse curated fashion products, manage a persistent shopping cart, apply discount coupons, and complete purchases securely through Stripe integration. The application also provides an admin dashboard for product management, featured collections, and basic sales analytics.

This project demonstrates industry-standard full-stack development practices, including modular architecture, RESTful APIs, secure authentication, and performance optimization.

---

## Key Features

### User Features
- Secure user registration and login using JWT authentication  
- Product browsing with category-based filtering  
- Persistent shopping cart across sessions  
- Coupon application and discount validation  
- Secure checkout using Stripe payment gateway  
- Order placement and order history tracking  
- Fully responsive user interface  

### Admin Features
- Product creation, update, and deletion  
- Category and featured product management  
- Order monitoring and status updates  
- Sales and product overview analytics  

---

## Technology Stack

### Frontend
- React.js  
- Tailwind CSS  
- Zustand (state management)  
- React Router DOM  
- Axios  

### Backend
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- JSON Web Tokens (JWT)  
- Redis (caching)  
- Stripe (payment processing)  
- Cloudinary (image storage)  

---

## System Architecture

UrbanVista follows a client–server architecture:

- The React frontend handles user interaction and UI rendering.
- The Express backend exposes RESTful APIs and enforces business logic.
- MongoDB stores user, product, order, and coupon data.
- Redis caches frequently accessed data for improved performance.
- Stripe securely manages online payments.

---

## Installation and Setup

### Prerequisites
- Node.js (v18 or higher recommended)
- MongoDB (local or MongoDB Atlas)
- Redis instance
- Stripe account
- Cloudinary account

## Deployment

A production-ready deployment of UrbanVista is live at:

<a href="https://urbanvista-30br.onrender.com" target="_blank" rel="noopener noreferrer">https://urbanvista-30br.onrender.com</a>

This hosted instance on **Render** demonstrates the full-stack application's capabilities in a cloud environment, including real-time cart persistence, secure Stripe payments, admin analytics, and responsive UI across devices. It serves as a practical example of modern MERN stack deployment practices for scalable e-commerce platforms.

