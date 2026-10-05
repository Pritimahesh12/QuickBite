# 🍔 QuickBite – Canteen Pre-Ordering System

**QuickBite** is a full-stack **canteen pre-ordering web application** built using the **MERN stack**. It allows students to browse the canteen menu, add food items to their cart, and place orders in advance.

The main goal of QuickBite is to **reduce waiting time and improve the canteen ordering experience** by allowing users to place their orders before reaching the counter.

---

## 🌐 Live Demo

**Live Website:** https://canteen-preordering-system.vercel.app

**GitHub Repository:** https://github.com/Pritimahesh12/QuickBite

---

## ✨ Features

### 👤 User Features

- User registration and login
- Secure authentication using JWT
- Browse available food items
- View food details and prices
- Add items to cart
- Increase or decrease item quantity
- Remove items from cart
- Place orders in advance
- View and track placed orders

### 🛠️ Admin Features

- Separate admin panel
- Admin authentication
- Add new food items
- Update food item details
- Delete food items
- View incoming orders
- Manage customer orders
- Update order status

---

## 🚀 Why QuickBite?

Traditional canteen ordering often requires students to:

1. Stand in a queue
2. Wait for their turn
3. Place the order
4. Wait for the food to be prepared

QuickBite simplifies this process by allowing students to **browse the menu and place their orders in advance**.

### Benefits

- ⏱️ Reduces waiting time
- 📱 Convenient online ordering
- 🛒 Easy cart management
- 📦 Better order management
- 👨‍💼 Dedicated admin panel
- 🔐 Secure user authentication

---

## 🏗️ Project Architecture

```text
                    ┌─────────────────────┐
                    │      User           │
                    │   Web Application   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      Frontend       │
                    │      React.js       │
                    └──────────┬──────────┘
                               │
                         REST API
                               │
                               ▼
                    ┌─────────────────────┐
                    │       Backend       │
                    │ Node.js + Express.js│
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      MongoDB        │
                    │      Database       │
                    └─────────────────────┘


                    ┌─────────────────────┐
                    │       Admin         │
                    │    Admin Panel      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Node.js + Express.js│
                    │     REST APIs       │
                    └─────────────────────┘
```

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Admin Panel | React.js |
| Backend | Node.js |
| API | Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Authentication | JSON Web Token (JWT) |
| Frontend Deployment | Vercel |
| Backend Deployment | Render |

---

## 📂 Project Structure

```text
QuickBite/
│
├── admin/
│   └── Admin panel source code
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── .gitignore
└── README.md
```

---

## 🔐 Authentication

QuickBite uses **JWT (JSON Web Token)** based authentication.

The authentication system allows:

- User registration
- User login
- Protected API routes
- Authentication of users
- Admin access control

---

## 🛒 Ordering Workflow

```text
User
  │
  ▼
Login / Register
  │
  ▼
Browse Menu
  │
  ▼
Select Food Items
  │
  ▼
Add Items to Cart
  │
  ▼
Place Order
  │
  ▼
Order Stored in Database
  │
  ▼
Admin Receives Order
  │
  ▼
Admin Updates Order Status
  │
  ▼
User Tracks Order
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Pritimahesh12/QuickBite.git

cd QuickBite
```

---

### 2. Backend Setup

Navigate to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

Start the backend server:

```bash
npm start
```

or, if the project uses nodemon:

```bash
npm run dev
```

---

### 3. Frontend Setup

Open a new terminal and navigate to the frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

### 4. Admin Panel Setup

Navigate to the admin folder:

```bash
cd admin
```

Install dependencies:

```bash
npm install
```

Start the admin application:

```bash
npm run dev
```

---

## 🔑 Environment Variables

For security, sensitive information should be stored in environment variables instead of being directly written in the source code.

Example:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

> **Note:** Never upload your `.env` file or database credentials to GitHub.

---

## 📡 Main Functional Modules

### User Module

Handles:

- Registration
- Login
- Authentication
- Profile
- Cart
- Orders

### Food/Menu Module

Handles:

- Food listing
- Food details
- Food availability
- Food management

### Cart Module

Handles:

- Adding food items
- Removing food items
- Updating quantities
- Calculating order totals

### Order Module

Handles:

- Creating orders
- Storing order details
- Viewing orders
- Tracking order status

### Admin Module

Handles:

- Food management
- Order management
- Order status updates
- Administrative operations

---

## 🔮 Future Improvements

The following features can be added in future versions:

- 💳 Online payment integration
- 📧 Email notifications
- 🔔 Real-time order notifications
- 📱 Mobile application
- 📊 Admin analytics dashboard
- ⭐ Food ratings and reviews
- 🔍 Advanced food search and filtering
- 📍 Order pickup time selection

---

## 🎯 Project Objective

The objective of QuickBite is to develop a simple and efficient digital solution for college canteens.

The application demonstrates practical implementation of:

- Full-stack web development
- REST API development
- Database management
- Authentication and authorization
- CRUD operations
- State management
- Admin management
- Cloud deployment

---

## 👨‍💻 Author

**Pritimahesh**

GitHub: [@Pritimahesh12](https://github.com/Pritimahesh12)

---

## 📄 License

This project is developed for educational and academic purposes.
