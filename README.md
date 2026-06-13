# 🍕 Foodie Hub — Food Ordering Web Application

Foodie Hub is a full-stack food ordering web application that allows users to browse restaurants, view menus, manage carts, place orders, make payments, and track deliveries in real-time. It also includes reward points, coupon systems, and an admin panel for order management.

This project is built to simulate a real-world online food delivery system with a smooth, responsive, and user-friendly experience.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, EJS  
- **Backend:** Node.js, Express.js  
- **Database:** MySQL  
- **Authentication:** bcrypt, express-session  
- **Mapping:** Leaflet.js + OpenStreetMap  
- **Other Tools:** JavaScript, REST APIs  

---

## ✨ Features

### 🍽️ User Features
- Browse restaurants and food items
- Search and filter menu items
- Add/remove items from cart
- Update quantity in cart
- Place orders with validation
- User signup and login system

### 💳 Payment System
- Cash on Delivery (COD)
- UPI payment support
- QR code based payment option

### 🎟️ Coupons & Rewards
- Discount coupon system
- Scratch card based gift coupons
- Reward points for every order
- Redeem points for discounts

### 📍 Live Order Tracking
- Real-time delivery tracking using map
- Live rider movement simulation
- Order status updates (Placed → Preparing → On the Way → Delivered)

### 👤 User Profile
- Order history tracking
- Total orders, savings, and spend analysis
- Reward points dashboard

### 🛠️ Admin Panel
- View all orders
- Update order status
- Manage order workflow

---

## 📂 Project Structure
Foodie-Hub/
├── public/
│ ├── css/
│ ├── images/
│
├── views/
│ ├── partials/
│ ├── home.ejs
│ ├── restaurants.ejs
│ ├── menu.ejs
│ ├── cart.ejs
│ ├── checkout.ejs
│ ├── profile.ejs
│ ├── track-order.ejs
│ ├── success.ejs
│ └── myOrders.ejs
│
├── server.js
├── schema.sql
├── aiven_schema.sql
├── package.json
├── .env
└── README.md
---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/ankita12365/Foodie-Hub1.git
cd Foodie-Hub1
2. Install dependencies
npm install
3. Create MySQL database
CREATE DATABASE food_ordering_system;

Import schema:

mysql -u root -p food_ordering_system < schema.sql
4. Create .env file
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=food_ordering_system
DB_PORT=3306

SESSION_SECRET=your_secret_key

PORT=3000
5. Run the project
npm start

Open in browser:

http://localhost:3000
👩‍💻 Developer

Ankita Nitin Chavan

GitHub: https://github.com/ankita12365
