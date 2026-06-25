# 🎮 Neon Vault

A modern **full-stack digital game e-commerce platform** built with **ASP.NET Core MVC (.NET 8)**. Neon Vault provides a seamless shopping experience for purchasing and managing digital games through a cyberpunk-inspired interface, featuring a secure checkout system, persistent digital library, and an administrative dashboard for inventory management.

---

## ✨ Features

### 🛒 Digital Storefront

* Browse a catalog of digital games
* View detailed game information including price, genre, developer, release date, and cover image
* Responsive cyberpunk-inspired UI

### 🛍 Shopping Cart

* Session-based shopping cart for guest users
* Add and remove games without authentication
* Automatic subtotal calculation
* Secure HTTP session management

### 💳 Checkout System

* Collect customer information
* Generate digital orders and receipts
* Preserve historical pricing using snapshot order records
* Automatic cart clearing after successful purchase

### 📚 Digital Library

* Permanent ownership tracking
* View purchased games in a personal library
* Purchase history management

### ⚙️ Admin Dashboard

* Secure administrative interface
* Full CRUD functionality
* Manage games, pricing, descriptions, and cover images
* Inventory management

### 🔒 Security & Performance

* Server-side validation
* SQL Injection protection using Entity Framework Core
* Secure HTTP-only session cookies
* Asynchronous controllers and database operations
* Automated Entity Framework Core migrations

---

# 🛠 Tech Stack

| Category         | Technologies                                             |
| ---------------- | -------------------------------------------------------- |
| Framework        | ASP.NET Core MVC (.NET 8)                                |
| Language         | C#                                                       |
| ORM              | Entity Framework Core                                    |
| Database         | Microsoft SQL Server                                     |
| Frontend         | Razor Views (CSHTML), HTML5, CSS3, Bootstrap, JavaScript |
| State Management | Distributed Memory Cache, HTTP Sessions                  |
| Architecture     | MVC Pattern                                              |

---

# 📂 Project Structure

```
Neon-Vault
│
├── Controllers/
├── Models/
├── Views/
├── Data/
├── Services/
├── wwwroot/
│   ├── css/
│   ├── js/
│   └── images/
├── Migrations/
├── Program.cs
├── appsettings.json
└── README.md
```

---

# 🚀 Getting Started

## Prerequisites

* .NET 8 SDK
* Microsoft SQL Server
* Visual Studio 2022 or Visual Studio Code

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Neon-Vault.git
```

Navigate to the project

```bash
cd Neon-Vault
```

Restore dependencies

```bash
dotnet restore
```

Apply database migrations

```bash
dotnet ef database update
```

Run the application

```bash
dotnet run
```


# 🎯 Learning Outcomes

This project demonstrates practical experience in:

* Full-Stack Web Development
* ASP.NET Core MVC
* Entity Framework Core
* SQL Server Database Design
* Session-Based Authentication
* CRUD Operations
* MVC Architecture
* Responsive Web Design
* Secure Backend Development
* RESTful Design Principles

---

# 📈 Future Improvements

* User Authentication & Authorization
* Payment Gateway Integration (Stripe / PayPal)
* Wishlist System
* Game Reviews & Ratings
* Search & Advanced Filtering
* Email Order Confirmation
* Downloadable Digital Licenses
* Cloud Deployment
* Docker Support
* CI/CD Pipeline

---

# 👨‍💻 Author

**Bilawal Feroze**

Software Developer

