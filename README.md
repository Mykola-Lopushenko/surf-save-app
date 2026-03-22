# 🌊 Surf & Save

Full-stack web application for managing a surf retail system, including customers, products, orders, and order items.

## Features

- Manage customers, products, and orders through a relational database interface
- Implemented CRUD functionality for core entities, with several completed create, read, update, and delete operations
- Server-side rendered UI using Handlebars
- Relational database design with multiple linked tables
- Form handling and dynamic data display

## Tech Stack

- Backend: Node.js, Express
- Frontend: HTML, CSS, React
- Database: MySQL

## Database Design

Core entities:
- Customers
- Orders
- OrderItems
- Products
- ProductTypes

Relationships include:
- One-to-many between Customers and Orders
- Many-to-many between Orders and Products through OrderItems