# 🌊 Surf & Save

Live Demo: https://surf-save-app-production.up.railway.app/

Full-stack web application for managing a surf retail system, including customers, products, orders, and order items.

---

## 🚀 Features

- Manage customers, products, orders, and order items
- Full CRUD functionality (Create, Read, Update, Delete)
- Relational database with MySQL
- Server-side rendering with Handlebars
- Deployed online with Railway

---

## 🛠️ Tech Stack

- Backend: Node.js, Express
- Frontend: Handlebars (HBS), HTML, CSS
- Database: MySQL
- Deployment: Railway
- Version Control: Git + GitHub

---

## 🌐 Live Application

https://surf-save-app-production.up.railway.app/

Try:
- /customers
- /orders
- /products
- /producttypes
- /orderitems

---

## 🧩 Database Design

This project uses a relational schema with the following entities:

- Customers
- Orders
- OrderItems
- Products
- ProductTypes

Includes:
- Primary & foreign keys
- One-to-many relationships
- Data integrity constraints

---

## ⚙️ How to Run Locally

1. Clone the repository

- git clone https://github.com/Mykola-Lopushenko/surf-save-app.git
- cd surf-save-app

2. Install dependencies

- npm install

3. Create a .env file:

- DB_HOST=localhost
- DB_PORT=3306
- DB_USER=root
- DB_PASSWORD=your_password
- DB_NAME=surf_save
- PORT=3000

4. Set up your MySQL database using the provided DDL script

5. Run the app

- node app.js

6. Open in browser:

http://localhost:3000

---

## 📦 Deployment

The application is deployed on Railway with:
- Cloud-hosted MySQL database
- Environment variables for secure configuration
- Automatic deployment from GitHub

---

## 📈 Future Improvements

- Add authentication (login/register)
- Improve UI/UX
- Add validation and error handling
- Convert to REST API + React frontend

---

## 👤 Author

Mykola Lopushenko
