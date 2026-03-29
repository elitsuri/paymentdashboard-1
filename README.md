# PaymentDashboard 1

> Payment analytics dashboard with transactions, refunds, and disputes

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
React, TypeScript, FastAPI, PostgreSQL, Stripe

## 🏗️ Architecture
Backend service with React, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/paymentdashboard-1
cd paymentdashboard-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
