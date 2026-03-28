# 📦 Inventory Management Dashboard

A modern inventory management dashboard built using **Next.js, React, Redux, PostgreSQL, and Prisma**.
This project is currently under development and focuses on managing products, stock, and basic analytics.

---

## 🚀 Current Status

⚠️ This project is **not fully production-ready yet**.
It is currently in the **development phase**, with core dashboard and product management features implemented.

Planned to evolve into a **full SaaS-based eCommerce & inventory system**.

---

## ✨ Features (Implemented)

* 📊 Dashboard UI for inventory insights
* 📦 Product listing
* ➕ Add new products (currently basic functionality)
* 🖼️ Static product images (from local assets)
* 🔄 State management using Redux
* 🎨 Responsive UI with modern design

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* Redux Toolkit
* Tailwind CSS

### Backend

* Next.js API Routes

### Database

* PostgreSQL

### ORM

* Prisma

---

## 📁 Project Structure

```
Inventory-Management/
│
├── client/                     # Frontend (Next.js + Redux)
│   ├── public/                # Static assets
│   ├── src/
│   │   ├── app/               # App router (Next.js)
│   │   │   ├── components/    # Reusable UI components
│   │   │   ├── dashboard/     # Dashboard pages & analytics
│   │   │   ├── products/      # Product management UI
│   │   │   ├── inventory/     # Inventory tracking UI
│   │   │   ├── expenses/      # Expense management UI
│   │   │   ├── users/         # User management UI
│   │   │   ├── settings/      # App settings
│   │   │   ├── layout.tsx     # Root layout
│   │   │   ├── page.tsx       # Main entry page
│   │   │   └── dashboardWrapper.tsx
│   │   │
│   │   ├── state/             # Redux store & API logic
│   │   │   ├── api.ts
│   │   │   └── index.ts
│   │
│   ├── next.config.ts         # Next.js configuration
│   ├── package.json
│   └── .env.local
│
├── server/                    # Backend (Node.js + Express + Prisma)
│   ├── src/
│   │   ├── controllers/       # Request handlers
│   │   │   ├── dashboardController.ts
│   │   │   ├── productController.ts
│   │   │   ├── expenseController.ts
│   │   │   └── userController.ts
│   │   │
│   │   ├── routes/            # API routes
│   │   └── index.ts           # Server entry point
│   │
│   ├── prisma/                # Database schema & migrations
│   │   ├── schema.prisma
│   │   ├── migrations/
│   │   └── seed.ts
│   │
│   ├── seedData/              # Initial data (JSON files)
│   ├── generated/             # Prisma generated client
│   ├── dist/                  # Compiled output
│   ├── .env                   # Environment variables
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository

```
git clone https://github.com/Ashish-Tiwari80/Inventory-management.git
cd Inventory-management
```

2. Install dependencies

```
npm install
```

3. Setup environment variables

Create a `.env` file:

```
DATABASE_URL=your_postgresql_connection_string
```

4. Run Prisma migrations

```
npx prisma migrate dev
```

5. Start the development server

```
npm run dev
```

---

## 🔮 Future Improvements

Planned features to make it production-ready:

* 🔐 Authentication & User Profiles
* 🛒 Order Management System
* 💳 Payment Integration
* ☁️ Cloud image upload (AWS / Cloudinary)
* 📈 Advanced analytics (sales, revenue, trends)
* 🧑‍💼 Admin & Customer roles
* 🌐 Multi-user SaaS architecture

---

## 🎯 Goal

To transform this project into a **full-stack SaaS-based Inventory + eCommerce platform**.

---

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are welcome!

---

⭐ If you find this project helpful, consider giving it a star!
