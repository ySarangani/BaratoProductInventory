# 🛒 Barato Product Inventory App

**Barato Product Inventory app** is a full-stack product inventory management app built with modern .NET technologies, containerized for easy deployment, and designed for clarity and performance. Whether you're adding, updating, or tracking products, Barato makes inventory simple and efficient.

---

## 📷 Preview

> Coming soon: Screenshots or a short demo GIF here  
> (Blazor UI listing products, modal for create/edit, loading indicators)

---

## 📦 Features

- ✅ **Product CRUD** (Create, Read, Update, Delete)
- 🔍 **Search & Sort** products by name, category, price
- ⚡ **Redis caching** for blazing-fast product list access
- 🗄️ **SQL Server (via EF Core)** for persistent storage
- 🌐 **RESTful API** with validation and proper error responses
- 🧪 **Unit-tested business logic** using NUnit + Moq
- 🐳 **Dockerized stack** for API, frontend, Redis, and DB

---

## 🛠 Tech Stack

| Layer      | Technology                 |
|------------|----------------------------|
| Backend    | ASP.NET Core Web API (.NET 8) |
| Frontend   | Blazor Server              |
| Database   | SQL Server (Docker)        |
| ORM        | Entity Framework Core      |
| Caching    | Redis                      |
| Testing    | NUnit + Moq                |
| DevOps     | Docker & Docker Compose    |
| VCS        | Git + GitHub               |

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/barato-inventory.git
cd barato-inventory
```