<h1 align="center">🚗 Garage API</h1>

<p align="center">
  <b>A comprehensive RESTful API for managing garage operations, built with ASP.NET Core.</b><br/>
</p>

---

## 📖 Overview

**Garage API** is a robust backend solution for automotive service centers. It handles:

- Customer management  
- Vehicle tracking  
- Service record maintenance  

All managed through a secure and performant REST API built on modern technologies.

---

## 🛠️ Technologies Used

- **ASP.NET Core 9.0** – High-performance web framework  
- **Entity Framework Core** – ORM for database operations  
- **SQL Server** – Primary data store  
- **Redis** – Distributed caching  
- **JWT Authentication** – Secure API access  
- **Swagger / OpenAPI** – Auto-generated API documentation  
- **FluentValidation** – Clean and expressive input validation  
- **AutoMapper** – Efficient object-to-object mapping  
- **Serilog** – Structured logging and diagnostics  
- **Feature Management** – Toggle and roll out features safely  

---

## 🧱 Architecture

Follows a clean architecture approach:

- **Core**: Domain entities & interfaces  
- **Infrastructure**: Data access and integrations  
- **Application**: Business logic and services  
- **API**: Exposes REST endpoints and handles HTTP requests  

---

## 🔗 API Endpoints

### 🔐 Authentication
- `POST /api/v1/Auth/register` – Register a new user  
- `POST /api/v1/Auth/login` – Authenticate and receive JWT token  

### 👤 Customers
- `GET /api/v1/Customers` – Get all customers  
- `GET /api/v1/Customers/{id}` – Get customer by ID  
- `POST /api/v1/Customers` – Create a new customer  
- `PUT /api/v1/Customers/{id}` – Update customer  
- `DELETE /api/v1/Customers/{id}` – Delete customer  

### 🚘 Vehicles
- `GET /api/v1/Vehicles` – Get all vehicles  
- `GET /api/v1/Vehicles/{id}` – Get vehicle by ID  
- `POST /api/v1/Vehicles` – Create a new vehicle  
- `PUT /api/v1/Vehicles/{id}` – Update vehicle  
- `DELETE /api/v1/Vehicles/{id}` – Delete vehicle  

### 🛠️ Service Records
- `GET /api/v1/ServiceRecords` – Get all service records  
- `GET /api/v1/ServiceRecords/{id}` – Get service record by ID  
- `POST /api/v1/ServiceRecords` – Create a new service record  
- `PUT /api/v1/ServiceRecords/{id}` – Update service record  
- `DELETE /api/v1/ServiceRecords/{id}` – Delete service record  

---

## 🔒 Security Features

- JWT authentication with refresh tokens  
- Password hashing via ASP.NET Core Identity  
- Role-based authorization  
- API rate limiting  
- HTTPS enforcement  
- CORS policy setup  
- Input validation with FluentValidation  

---

## 🚀 Setup & Installation

### ✅ Prerequisites
- [.NET 9.0 SDK](https://dotnet.microsoft.com/)  
- SQL Server  
- Redis (optional for caching)  

---

## 📸 Screenshots


Dashboard

<p align="center">
   <img src="https://i.imgur.com/OeGksVT.jpeg" height="60%" width="60%" alt="Mechanic Dashboard Screenshot"/>
</p>


Swagger UI

<p align="center">
   <img src="https://i.imgur.com/OeGksVT.jpeg" height="60%" width="60%" alt="Mechanic Dashboard Screenshot"/>
</p>

Vehicle Management

<p align="center">
   <img src="https://i.imgur.com/OeGksVT.jpeg" height="60%" width="60%" alt="Mechanic Dashboard Screenshot"/>
</p>

---


### 📦 Installation Steps

```bash
# Clone the repository
git clone https://github.com/EliezerKibet/garage-api.git
cd garage-api
