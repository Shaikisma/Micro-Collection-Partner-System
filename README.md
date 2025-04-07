# 🚚 Micro Collection Partner (MCP) System

The **Micro Collection Partner System** is a full-stack application designed to help a Micro Collection Partner manage multiple Pickup Partners efficiently. The system allows real-time order tracking, wallet management, and partner monitoring for smooth and scalable operations.

## 📁 Project Structure

. ├── client # Frontend React app ├── server # Backend API using Express and TypeScript ├── shared # Shared utilities, types, and constants ├── temp_zip # Temporary zip logic ├── .gitignore
├── drizzle.config.ts ├── create-zip.js ├── tailwind.config.ts ├── postcss.config.js ├── vite.config.ts ├── tsconfig.json └── package.json


## ✨ Features

### ✅ MCP Dashboard
- View total balance in MCP's wallet
- Monitor Pickup Partner status
- Add/withdraw funds
- Assign/manage orders

### 🧑‍🤝‍🧑 Pickup Partner Management
- Add/delete Pickup Partners
- Set commissions
- Track partner activity

### 💰 Wallet & Transactions
- Manage funds for MCP & Pickup Partners
- Full transaction history

### 📦 Order Management
- Assign orders manually or auto-assign
- Live tracking of order status
- Reports for orders and earnings

### 🔔 Notifications
- Real-time alerts for order updates, low balance, etc.

## 🚀 Tech Stack

| Layer      | Tech                          |
|------------|-------------------------------|
| Frontend   | React + Tailwind CSS          |
| Backend    | Node.js + Express + TypeScript|
| Database   | Drizzle ORM (supports Postgres, MySQL) |
| Styling    | Tailwind CSS                  |
| Config     | Vite, tsconfig, drizzle config|

## 📦 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/Shaikisma/Micro-Collection-Partner-System.git
   cd Micro-Collection-Partner-System

Install dependencies
npm install
Start the server
npm run dev
📄 License
This project is for educational and demo purposes as part of a Full Stack Developer Internship Assignment by EpiCircle.

