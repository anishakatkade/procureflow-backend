# ProcureFlow Backend

## Overview

ProcureFlow is a procurement and supplier management platform designed to help manufacturers connect with suppliers, request quotations, compare offers, and manage purchase orders efficiently.

This repository contains the backend services built using Node.js, Express.js, and MongoDB.

---

## Features

* User Authentication (Register/Login)
* JWT Based Authorization
* Role-Based Access Control
* Supplier Management
* RFQ (Request For Quotation) Management
* Quotation Management
* Order Management
* MongoDB Atlas Integration
* RESTful APIs

---

## Tech Stack

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

### Authentication

* JWT (JSON Web Token)
* bcryptjs

### Tools

* Postman
* Git
* GitHub

---

## Project Structure

backend/

├── config/

├── controllers/

├── middleware/

├── models/

├── routes/

├── .env

├── .gitignore

├── package.json

└── server.js

---

## User Roles

### Manufacturer

* Create RFQs
* View Quotations
* Manage Orders

### Supplier

* View RFQs
* Submit Quotations
* Manage Supplier Profile

### Admin

* Manage Users
* Monitor Platform Activity

---

## Core Modules

### Authentication

* Register User
* Login User
* JWT Token Generation

### Supplier Management

* Add Supplier
* Update Supplier
* View Suppliers
* Delete Supplier

### RFQ Management

* Create RFQ
* Update RFQ
* Close RFQ
* View RFQs

### Quotation Management

* Submit Quotation
* Compare Quotations

### Order Management

* Create Orders
* Track Order Status
* Update Order Status

---

## API Endpoints

### Authentication

POST /api/auth/register

POST /api/auth/login

### Suppliers

GET /api/suppliers

POST /api/suppliers

PUT /api/suppliers/:id

DELETE /api/suppliers/:id

### RFQs

GET /api/rfqs

POST /api/rfqs

PUT /api/rfqs/:id

DELETE /api/rfqs/:id

### Orders

GET /api/orders

POST /api/orders

PUT /api/orders/:id

---

## Future Enhancements

* Redis Caching
* Docker Support
* AWS Deployment
* Email Notifications
* Analytics Dashboard
* AI-Based Supplier Recommendations


