# 🍕 React Pizza App

A modern pizza ordering app built with **React** and **React Router v6**. It supports menu browsing, cart management, and order creation and tracking — all within a clean, component-based UI.

## 🚀 Features

- 🏠 **Home Page** – Landing page with navigation to menu and orders
- 📋 **Menu Page** – Displays available pizzas (loaded from a server via `menuLoader`)
- 🛒 **Cart Page** – Shows selected items before ordering
- 📝 **Create Order Page** – Place a new order using the form (handled by `createOrderAction`)
- 🔍 **Order Detail Page** – View an existing order using its `orderId`, with update support
- 🧱 **Layout** – `AppLayout` wraps the entire app with consistent navigation and layout
- ❌ **Error Handling** – Friendly error UI via a shared `Error` component

## 🧩 Tech Stack

- **React**
- **React Router v6.4+**
- **Modular Component Structure**
- **Data Loaders and Actions** (React Router)

## 📁 Project Structure

```
src/
│
├── features/
│   ├── cart/
│   │   └── Cart.jsx
│   ├── menu/
│   │   ├── Menu.jsx
│   │   └── menuLoader.js
│   └── order/
│       ├── CreateOrder.jsx
│       ├── Order.jsx
│       ├── UpdateOrder.js
│       └── loaders.js
│
├── ui/
│   ├── AppLayout.jsx
│   ├── Home.jsx
│   └── Error.jsx
│
└── App.jsx


## 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).

---

Built with ❤️ using React Router.
