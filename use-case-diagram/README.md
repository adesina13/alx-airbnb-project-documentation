# 🎭 Airbnb Clone Backend — Use Case Diagram

## 📘 Overview
This document presents the **Use Case Diagram** for the Airbnb Clone backend system.  
The diagram visualizes interactions between different user roles (Guest, Host, Admin) and the system, highlighting the key functionalities like registration, property management, bookings, and payments.

---

## 👥 Actors

| Actor | Description |
|--------|-------------|
| **Guest** | Registers, books properties, makes payments, and leaves reviews. |
| **Host** | Lists and manages properties, views bookings, and handles requests. |
| **Admin** | Oversees users, properties, and overall platform moderation. |
| **Payment Gateway** | External service responsible for processing transactions securely. |

---

## ⚙️ Key Use Cases

### For Guests:
- Register account  
- Login / Logout  
- Search for properties  
- View property details  
- Make booking  
- Make payment (via Payment Gateway)  
- Cancel booking  
- Leave review  

### For Hosts:
- Register as host  
- Login / Logout  
- Add, update, or delete property listings  
- View bookings for their listings  
- Approve or reject bookings  

### For Admins:
- Login  
- Manage users (approve, suspend, delete)  
- Manage properties (approve or deactivate)  
- Review reports and platform statistics  

### For Payment Gateway:
- Process booking payment  
- Confirm transaction status  

---

## 🗺️ System Use Case Diagram

Below is the visual representation of how actors interact with the Airbnb backend system:

![Airbnb Use Case Diagram](./airbnb-use-case-diagram.png)

---

## 🧰 Tools Used
- **Draw.io (Diagrams.net)** — Diagram design  
- **Markdown** — Documentation formatting  
- **Git & GitHub** — Version control and submission

---

## 👨‍💻 Author
**Adesina Olagunju**  
Backend Developer | ALX Software Engineering Program
