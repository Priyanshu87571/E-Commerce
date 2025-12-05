MERN E-Commerce Platform

A full-featured E-Commerce Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).
This project demonstrates a modern online shopping experience with user authentication, product catalog, cart management, checkout flow, and order processing.

🚀 Features
🔐 Authentication & Authorization

User registration & login

Secure password hashing (bcrypt)

JWT-based authentication

Role-based access (Admin / User)

🛍️ Product Management

Browse products by category

Search & filter functionality

Product details page

Admin can add, edit, delete products

🛒 Cart & Checkout

Add/remove products from cart

Update quantity

Checkout page

Order creation & purchase flow

📦 Order Management

User order history

Admin order dashboard

Order status updates

🎨 Frontend UI

React-based responsive UI

Context API / Redux (based on your project)

Toast notifications

Modern styling (Tailwind / CSS / Bootstrap)

⚙️ Backend API

RESTful API with Express.js

MongoDB database models

Error handling middleware

Secure API endpoints

🛠️ Tech Stack
Frontend

React.js

React Router

Context API / Redux

Axios

Tailwind CSS / Bootstrap (choose what you used)

Backend

Node.js

Express.js

MongoDB + Mongoose

JWT Authentication

📁 Project Structure
ecommerce-mern/
├── client/               # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
├── server/               # Node + Express Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
├── README.md
└── .gitignore

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

2️⃣ Install Backend Dependencies
cd server
npm install


Create .env file:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000


Start backend:

npm start

3️⃣ Install Frontend Dependencies
cd ../client
npm install
npm start


Frontend runs at:

http://localhost:3000


Backend runs at:

http://localhost:5000
