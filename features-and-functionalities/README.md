# 🏠 Airbnb Clone Backend — Features and Functionalities

## 📘 Overview
This document outlines the core **features and functionalities** that the Airbnb Clone backend must support.  
The system mimics the behavior of Airbnb by allowing users to register, list properties, make bookings, process payments, and manage reviews through a secure RESTful API.

---

## ⚙️ Core Features

### 1. 👤 User Management
- User Registration & Login (JWT Authentication)
- Profile Management (update name, phone, bio)
- Role-based Access (Guest, Host, Admin)
- Password Hashing (using bcrypt)
- Email Verification & Password Reset

---

### 2. 🏡 Property Management
- Create, Update, Delete, and View property listings
- Property attributes: title, description, location, price, images, amenities, availability dates
- Search & filter properties by location, price, or type
- Host can view bookings for their properties

---

### 3. 📅 Booking System
- Guests can request bookings for available dates
- Hosts can approve or reject booking requests
- Track booking status (pending, confirmed, cancelled)
- Prevent overlapping bookings
- Generate booking receipts

---

### 4. 💳 Payment Processing
- Integration with **Stripe API**
- Secure payment transactions for bookings
- Refund and cancellation handling
- Payment history for users

---

### 5. 🌟 Reviews & Ratings
- Guests can review properties after stay
- 1–5 star rating system
- Average ratings displayed on each property

---

### 6. 🛡️ Security and Authentication
- JWT-based Authentication
- Role-based Authorization
- Password hashing (bcrypt)
- Input validation & sanitization

---

### 7. ⚙️ Admin Management
- Admin dashboard to manage users and listings
- Approve or suspend accounts
- Handle reports and flagged content

---

### 8. ✉️ Notifications
- Email confirmation for registration and booking
- Payment confirmation alerts
- Booking reminders (optional SMS/Email)

---

## 🗺️ System Feature Diagram
Below is the high-level system diagram illustrating the main modules and their relationships:

![Airbnb Backend Features Diagram](./airbnb-features.png)

---

## 🧰 Tools Used
- **Draw.io (Diagrams.net)** — for diagram design
- **Markdown** — for documentation formatting
- **Git & GitHub** — for version control

---

## 👨‍💻 Author
**Adesina Olagunju**  
Backend Developer | ALX Software Engineering Program
