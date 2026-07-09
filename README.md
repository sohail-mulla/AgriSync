# 🌾 AgriSync — Empowering Farmers, Buyers & Drivers Through Technology

AgriSync is a **full-stack B2B agriculture marketplace** connecting **Farmers, Buyers, and Drivers** — enabling smarter trading, efficient logistics, and real-time collaboration using **Spring Boot + React.js**.

> ✅ Tested successfully on localhost and ready for deployment.

---

## 🌍 Overview

AgriSync transforms traditional produce trading into a **digital ecosystem** with role-based dashboards, analytics, and automation for all three user types.

🔗 **GitHub Repository:** [AgriSync](https://github.com/surajshinde87/AgriSync)

---

## 🧩 Why AgriSync?

### 🌱 For Farmers
- Manage produce, bids, and earnings  
- Accept or reject bids  
- View and mark orders as delivered  
- Dashboard with analytics (orders, crops, earnings)

### 💰 For Buyers
- Place orders and bids  
- View order history  
- Receive live notifications via WebSocket  
- Provide feedback and ratings  
- Dashboard with insights and analytics

### 🚚 For Drivers
- Manage deliveries and payments  
- Update order statuses (ASSIGNED → PICKED_UP → IN_TRANSIT → DELIVERED)  
- Track total and per-order earnings  
- Dashboard with stats and ratings

### 🔐 For Everyone
- Secure login and registration  
- Email OTP verification using **Google App Password**  
- Forgot Password recovery via OTP  
- Role-based authentication (Farmer / Buyer / Driver)

> 💡 AgriSync bridges **technology and agriculture** — making produce trading smarter, faster, and more transparent.

---

## 🧠 Core Features

### 🔐 Common
- User registration & login (JWT authentication)
- Role-based authentication & authorization
- Email OTP verification using Google SMTP
- Forgot password with OTP

### 👨‍🌾 Farmer
- Add, edit, and delete produce  
- Accept/reject bids  
- View orders & analytics  

### 🧑‍💼 Buyer
- Browse and search produce  
- Place orders and bids  
- Receive live order notifications  
- View order history and analytics  

### 🚚 Driver
- Manage assigned orders  
- Update delivery status  
- Track earnings and ratings  

---

## ⚙️ Tech Stack

### 🖥 Backend
| Technology | Purpose |
|-------------|----------|
| **Java 17** | Core backend language |
| **Spring Boot 3.x** | Application framework |
| **Spring Web (REST)** | RESTful API development |
| **Spring Data JPA (Hibernate)** | ORM & persistence |
| **MySQL** | Relational database |
| **Spring Security + JWT** | Authentication & authorization |
| **Spring Mail (SMTP)** | Email OTP using Google App Password |
| **WebSocket / STOMP** | Real-time notifications |
| **Lombok** | Reduces boilerplate code |
| **Maven** | Build & dependency management |

### 💻 Frontend
| Technology | Purpose |
|-------------|----------|
| **React.js (latest)** | UI framework |
| **React Router DOM** | Routing |
| **Redux Toolkit** | State management |
| **Axios** | API calls |
| **Tailwind CSS** | Styling & responsiveness |
| **React Toastify** | Notifications |
| **Framer Motion** | Animations |
| **React Icons** | Icon library |
| **Socket.io-client** | Real-time WebSocket communication |

---

## 🧱 System Architecture

- Client (React.js)
- │
- │ REST + WebSocket APIs
- ▼
- Spring Boot (Controllers)
- ▼
- Service Layer (Business Logic)
- ▼
- Repository Layer (JPA)
- ▼
- MySQL Database

