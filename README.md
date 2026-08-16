# 🍔 Online Food Delivery & Tracking System

A full-stack web application for ordering food online with real-time order tracking, restaurant management, and an admin dashboard.

---

## 📋 Features

- **User Authentication:** Register, Login, JWT-based authentication
- **Restaurant Management:** Browse restaurants and menu items
- **Cart System:** Add/Remove items, update quantities
- **Order Placement:** Place orders with real-time tracking
- **Order Tracking:** Track order status (Pending → Preparing → Out for Delivery → Delivered)
- **Admin Dashboard:** Manage users, restaurants, and orders
- **Responsive UI:** Works on desktop and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React.js, React Router, Axios, CSS/Bootstrap |
| **Backend** | Node.js, Express.js |
| **Database** | MySQL |
| **Authentication** | JWT (JSON Web Tokens) |
| **Other** | Bcrypt, Dotenv |

---

## 📸 Screenshots

*(Add screenshots later)*

| Login Page | Home Page | Order Tracking |
| :---: | :---: | :---: |
| *(Add image)* | *(Add image)* | *(Add image)* |

---

## 🚀 How to Run (Step by Step)

### Prerequisites
- Node.js installed
- XAMPP (MySQL) installed and running
- VS Code or any code editor

### Step 1: Open Project in VS Code
```bash
code .
```
*(Or open folder manually in VS Code)*

### Step 2: Check MySQL is Running
Press `Win + R` → Type `services.msc` → Press Enter  
Find **MySQL** and make sure it's `Running`.

### Step 3: Start the Backend Server
Open terminal in VS Code and run:
```bash
node backend/server.js
```

### Step 4: Access the Project
Open your browser and go to:
```
http://localhost:5000
```

### Step 5: Check Database Tables (Optional)
Open Command Prompt and run:
```bash
mysql -u root -p
```
Enter password: `your_password_here`

```sql
SHOW DATABASES;
USE online_food_db;
SHOW TABLES;
SELECT * FROM table_name;
```

---

## 📁 Project Structure

```
online-food-delivery-system/
├── backend/          (Node.js server)
├── frontend/         (React app)
├── screenshots/      (Images)
├── demo/             (Video demo)
├── package.json
├── README.md
└── .gitignore
```

---

## 👩‍💻 My Contribution

As a Computer Science undergraduate, I developed this project from scratch to strengthen my full-stack development skills and solve a real-world problem — the need for a seamless online food ordering and tracking experience.

### 🔹 Backend Development (Node.js + Express)
- Designed and implemented RESTful APIs for user authentication, restaurant management, cart operations, order placement, and admin controls.
- Built a secure JWT-based authentication system with login, registration, and role-based access (Customer / Admin).
- Created middleware for authentication, error handling, and input validation.
- Integrated MySQL database using raw SQL queries and connection pooling for efficient data handling.
- Implemented real-time order status updates (Pending → Preparing → Out for Delivery → Delivered).

### 🔹 Frontend Development (React.js)
- Developed a fully responsive user interface using React.js, React Router, and Axios.
- Built reusable components for menus, carts, order history, and admin panels.
- Integrated REST APIs with the frontend for seamless data flow.
- Added form validation and user-friendly error messages.
- Implemented state management using React Context API (or Redux, if used).
- Designed a clean, modern UI with CSS/Bootstrap for a smooth user experience.

### 🔹 Database Design (MySQL)
- Designed a normalized database schema with tables for users, restaurants, menu items, orders, and order items.
- Wrote complex SQL queries for order tracking, filtering, and reporting.
- Ensured data integrity with foreign keys, constraints, and indexes.

### 🔹 Project Management & Delivery
- Managed the complete project lifecycle — from planning and design to development, testing, and deployment.
- Followed Git workflows for version control and collaboration.
- Wrote clean, well-documented code with clear comments and structure.
- Prepared project documentation, including README, screenshots, and a demo video for client presentation.

### 🔹 Why This Project Matters
This project demonstrates my ability to:
- Build a full-stack application from scratch.
- Work with modern web technologies (React, Node.js, MySQL).
- Solve real-world problems with user-centric design.
- Deliver clean, secure, and scalable code.

This project is part of my academic portfolio and reflects my passion for software development and continuous learning.
---

## 🔮 Future Improvements

- Add payment gateway (Stripe)
- Implement WebSockets for real-time notifications
- Add email/SMS confirmation
- Deploy on Vercel/Heroku
