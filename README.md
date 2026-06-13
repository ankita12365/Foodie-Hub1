# 🍕 Foodie Hub — Food Ordering Web Application

Foodie Hub is a full-stack food delivery platform that simulates a real-world online ordering system. It allows users to browse restaurants, order food, make payments, and track deliveries in real time. The platform also includes a complete admin workflow, rewards system, and coupon-based discounts.

---

## 🚀 Key Highlights

- Full-stack food ordering system (Swiggy/Zomato-style project)
- Real-time delivery tracking with live map simulation
- Secure authentication system
- Rewards & coupon engine
- Admin order management panel
- Responsive UI for all devices

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap
- EJS (Embedded JavaScript Templates)
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Authentication
- bcrypt
- express-session

### APIs & Tools
- Leaflet.js (Maps)
- OpenStreetMap API
- REST APIs

---

## ✨ Features

### 👤 User Features
- Browse restaurants and menus
- Search and filter food items
- Add/remove items from cart
- Update quantity in cart
- Secure signup and login system
- Place orders with validation
- View order history

---

### 💳 Payment System
- Cash on Delivery (COD)
- UPI payment support
- QR code-based payment option

---

### 🎟️ Coupons & Rewards
- Discount coupon system
- Scratch card rewards
- Reward points on every order
- Redeem points for discounts

---

### 📍 Live Order Tracking
- Real-time delivery tracking on map
- Rider movement simulation
- Live order status updates:
  Placed → Preparing → On the Way → Delivered

---

### 🛠️ Admin Panel
- View all orders
- Update order status
- Manage complete order workflow

---

## 📁 Project Structure

```text
Foodie-Hub/
│
├── public/
│   ├── css/
│   └── images/
│
├── views/
│   ├── partials/
│   ├── home.ejs
│   ├── restaurants.ejs
│   ├── menu.ejs
│   ├── cart.ejs
│   ├── checkout.ejs
│   ├── profile.ejs
│   ├── track-order.ejs
│   ├── success.ejs
│   └── myOrders.ejs
│
├── server.js
├── schema.sql
├── aiven_schema.sql
├── package.json
├── .env
└── README.md
```
---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/ankita12365/Foodie-Hub1.git
cd Foodie-Hub1
```

### 2. Install dependencies

```bash
npm install
```

### 3. Setup MySQL Database

```sql
CREATE DATABASE food_ordering_system;
```

### Import schema:

```bash
mysql -u root -p food_ordering_system < schema.sql
```

### 4. Create `.env` file

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=food_ordering_system
DB_PORT=3306

SESSION_SECRET=your_secret_key
PORT=3000
```

### 5. Run the project

```bash
npm start
```

### Open in browser

```
http://localhost:3000
```

---

## 👩‍💻 Developer

**Ankita Nitin Chavan**

GitHub:  
https://github.com/ankita12365

---

## ⭐ Future Improvements

- Payment gateway integration (Razorpay / Stripe)
- AI-based food recommendations
- Real GPS-based rider tracking
- Mobile app (React Native)
- Push notifications for orderst Native)
- Push notifications for orders
