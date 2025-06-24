# 🛒 ProShop — eCommerce Platform

A full-featured eCommerce website built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It offers a complete shopping experience including a shopping cart, user profiles, product reviews, admin controls, and integrated PayPal payments.

---

## 🚀 Features

- 🛍️ Full-featured **shopping cart**
- ⭐ Product **reviews and ratings**
- 🎯 **Top products** carousel on the homepage
- 📄 **Product pagination** and search functionality
- 👤 **User profile** with past orders
- 🔧 Admin features:
  - Product management
  - User management
  - View and mark orders as delivered
- 💳 Checkout process with **shipping**, **payment method**, and **order summary**
- 💸 **PayPal** / credit card integration
- 🗃️ **Database seeder** for test users and products

---

## 🧰 Technology Stack

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)

### Frontend:
- React.js
- Redux (for state management)

---

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ProShop.git
cd ProShop
```

### 2. Setup Environment Variables

Create a `.env` file in the root directory with:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
```

### 3. Install Dependencies

```bash
# Install root and backend packages
npm install

# Install frontend packages
cd frontend
npm install
cd ..
```

### 4. Run the Application

To run both frontend and backend with one command:

```bash
npm run dev
```

To run backend only:

```bash
npm run server
```

---

## 🌱 Seed the Database

```bash
# Import sample data
npm run data:import

# Destroy all data
npm run data:destroy
```

---

## 👥 Sample Users

| Email              | Password | Role    |
|-------------------|----------|---------|
| admin@example.com | 123456   | Admin   |
| john@example.com  | 123456   | Customer |
| jane@example.com  | 123456   | Customer |

---

## 📄 Notes on ES Modules

This project uses **ECMAScript Modules (ESM)**. Make sure you have Node.js v14.6+ installed. When importing local files, use `.js` extensions to avoid module resolution errors.

---

## 📫 Contact

**Aditi Patel**  
📧 pateladiti542@gmail.com
