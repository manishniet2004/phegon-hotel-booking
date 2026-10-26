# 🏨 Phegon Hotel Booking & Management System

A full-stack hotel booking and management web application built with **Java Spring Boot**, **React.js**, and **MySQL**. This system provides seamless room browsing, secure user authentication with JWT, role-based access control (Admin & User), room management, and automated booking processing.

---

## 🚀 Tech Stack

### **Backend:**
* **Java 17+** / **Spring Boot** (REST APIs, Spring Security, JWT)
* **Spring Data JPA** / **Hibernate** (ORM & Database Management)
* **MySQL Database** (`phegon_hotel_db`)
* **AWS S3** (Cloud storage for room image uploads)

### **Frontend:**
* **React.js** (Functional Components, Hooks)
* **React Router** (Navigation & Protected Routes)
* **Axios** (API Integration)
* **Bootstrap / CSS** (Responsive UI Design)

---

## ✨ Key Features

### **👤 User Features:**
* **Authentication & Authorization:** Secure User Registration and Login using JWT tokens.
* **Browse Rooms:** View available rooms with advanced filtering and pagination.
* **Room Booking:** Select check-in/check-out dates, add guest details, and instantly generate a unique **Booking Confirmation Code**.
* **Profile Management:** View personal booking history and account details.

### **🛠️ Admin Features:**
* **Admin Dashboard:** Centralized control panel for managing hotel operations.
* **Room Management:** Add new rooms (with cloud image uploads), update room details, or delete rooms.
* **Booking Management:** View, search, and manage all customer bookings across the system.
* **Role-Based Security:** Protected admin routes ensuring only authorized admin accounts can access management panels.

---

## 📂 Project Structure

```text
phegon-hotel-booking/
│
├── backend/                  # Spring Boot Backend Source Code
│   ├── src/main/java/        # Controllers, Services, Repositories, Entities
│   └── src/main/resources/   # application.properties
│
└── frontend/                 # React.js Frontend Source Code
    ├── public/
    └── src/
        ├── component/        # Admin, Auth, Common, Booking & Home components
        ├── App.js
        └── index.js
