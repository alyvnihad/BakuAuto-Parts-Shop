# BakuAuto

> **BakuAuto** is a full-stack automotive parts e-commerce platform built to provide a modern, reliable, and user-friendly solution for discovering and managing vehicle spare parts.

---

## 📖 Overview

**BakuAuto** is a real-world automotive parts e-commerce platform designed to simplify the process of discovering, managing, and purchasing vehicle spare parts.

The platform follows a modern **frontend–backend architecture**, with a React.js and TypeScript frontend communicating with a Java Spring Boot backend through RESTful APIs.

The frontend and backend source code are maintained in **private repositories** due to the project's real-world usage and production-oriented nature.

This repository serves as the main project repository and provides an overview of the platform, architecture, technologies, and development scope.

---

## ✨ Features

* 🚗 Automotive spare parts catalog
* 🔍 Product search and filtering
* 🏷️ Product categorization
* 📦 Product and inventory management
* 🛒 Shopping cart functionality
* 👤 User registration and authentication
* 🔐 Authentication and authorization
* 📋 Order management
* 💳 E-commerce workflow
* 📱 Responsive user interface
* ⚡ RESTful API communication
* 🗄️ PostgreSQL database integration
* 🐳 Docker-based environment

---

## 🏗️ Architecture

BakuAuto follows a separated frontend and backend architecture.

```text
                              BakuAuto
                                 │
                 ┌───────────────┴───────────────┐
                 │                               │
          ┌──────▼───────┐               ┌───────▼────────┐
          │   Frontend   │               │     Backend    │
          │              │               │                │
          │ React.js     │◄─────────────►│ Java           │
          │ TypeScript   │   REST API    │ Spring Boot    │
          │              │               │ REST API       │
          └──────────────┘               └───────┬────────┘
                                                 │
                                          ┌──────▼───────┐
                                          │  PostgreSQL  │
                                          │   Database   │
                                          └──────┬───────┘
                                                 │
                                          ┌──────▼───────┐
                                          │    Docker    │
                                          └──────────────┘
```

---

## 🛠️ Technology Stack

### Frontend

The frontend is built with:

* **React.js**
* **TypeScript**
* REST API integration
* Component-based architecture
* Responsive UI design

The frontend is responsible for the user-facing experience, including product browsing, authentication, shopping cart functionality, and order-related workflows.

The frontend source code is maintained in a **private repository**.

### Backend

The backend is built using the Java ecosystem:

* **Java**
* **Spring Framework**
* **Spring Boot**
* **REST API**
* **PostgreSQL**
* **Docker**

The backend handles business logic, authentication, authorization, API requests, data persistence, and communication with the frontend.

The backend source code is maintained in a **private repository**.

### Database

**PostgreSQL** is used as the primary relational database for storing and managing application data, including:

* Users
* Products
* Categories
* Inventory
* Orders
* Order items
* Application-related entities

### Containerization

**Docker** is used to provide a consistent and isolated environment for application services and database infrastructure.

---

## 📂 Project Structure

The platform is organized into separate application layers:

```text
BakuAuto
│
├── Frontend
│   ├── React.js
│   └── TypeScript
│
├── Backend
│   ├── Java
│   ├── Spring Boot
│   └── REST API
│
├── Database
│   └── PostgreSQL
│
└── Infrastructure
    └── Docker
```

The frontend and backend are developed and maintained independently while communicating through RESTful APIs.

---

## 🔐 Security & Privacy

BakuAuto is a real-world project, so its application source code is maintained in private repositories.

The following information is intentionally not publicly exposed:

* Private source code
* Environment variables
* Database credentials
* API credentials
* Authentication secrets
* Production configuration
* Internal infrastructure configuration

Sensitive information should never be committed to the public repository.

---

## 🚀 Deployment

The frontend live application is deployed and accessible through Vercel.

**Production URL:**
https://auto-parts-shop-sage.vercel.app/login

The backend and database infrastructure are maintained separately in private environments.

---

## 📈 Project Status

**Status: Active Development**

BakuAuto is an actively developed platform with ongoing improvements, new features, optimizations, and technical enhancements.

---

## 📄 License

This project is proprietary software.

The source code, architecture, business logic, design, and associated project assets are not licensed for unauthorized use, reproduction, modification, or distribution.

© BakuAuto. All rights reserved.
