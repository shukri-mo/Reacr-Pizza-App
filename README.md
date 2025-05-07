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
```

## 🔧 Installation & Usage

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/react-pizza-app.git
cd react-pizza-app
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

## 🌐 Environment Variables

Create a `.env` file in the root of your project and add any required variables:

```
VITE_API_URL=https://your-api-url.com
```

Update and use this as needed for `menuLoader`, `createOrderAction`, etc.

## 📦 Build

```bash
npm run build
```

## 🔗 Live Demo

[👉 View Demo](https://your-deployment-link.com)

_Replace the link with your actual deployment (e.g., Vercel, Netlify, GitHub Pages)._

## 📸 Screenshots

![Home Page](screenshots/home.png)
![Menu Page](screenshots/menu.png)
![Order Page](screenshots/order.png)

## 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).

---

Built with ❤️ using React Router.
