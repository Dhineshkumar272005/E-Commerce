# 🛒 ShopHub — E-Commerce Web Application

A modern, fully functional e-commerce web application built with **React 19** and **Vite**. ShopHub allows users to browse products, manage a shopping cart, and complete checkout — all with a clean, responsive UI.

![React](https://img.shields.io/badge/React-19.2-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8.0-646CFF?logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-7.13-CA4245?logo=reactrouter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- **🏠 Product Catalog** — Browse a curated collection of tech products with images, prices, and descriptions
- **📄 Product Details** — View detailed product information on dedicated pages
- **🛒 Shopping Cart** — Add/remove items, adjust quantities, and see real-time totals
- **💳 Checkout** — Review your order, modify quantities, and place orders
- **🔐 User Authentication** — Sign up, log in, and log out with localStorage-based persistence
- **📱 Responsive Design** — Fully responsive across desktop, tablet, and mobile devices
- **⚡ Fast & Modern** — Powered by Vite for instant HMR and blazing-fast builds

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React 19](https://react.dev/) | UI library |
| [Vite 8](https://vite.dev/) | Build tool & dev server |
| [React Router DOM 7](https://reactrouter.com/) | Client-side routing |
| [React Hook Form 7](https://react-hook-form.com/) | Form handling & validation |
| [ESLint](https://eslint.org/) | Code linting |

---

## 📁 Project Structure

```
E-Commerce/
├── public/                  # Static assets
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Navbar.jsx       # Navigation bar with auth state
│   │   └── ProductCard.jsx  # Product card with cart integration
│   ├── context/             # React Context providers
│   │   ├── AuthContext.jsx  # Authentication state management
│   │   └── CartContext.jsx  # Shopping cart state management
│   ├── data/                # Static data
│   │   └── products.js      # Product catalog data
│   ├── pages/               # Page components
│   │   ├── Auth.jsx         # Login / Sign Up page
│   │   ├── Checkout.jsx     # Shopping cart & checkout page
│   │   ├── Home.jsx         # Home page with product grid
│   │   └── ProductDetails.jsx # Individual product page
│   ├── App.jsx              # Root component with routing
│   ├── App.css              # Global styles
│   ├── main.jsx             # Application entry point
│   └── index.css            # Base CSS reset
├── index.html               # HTML entry point
├── package.json             # Dependencies & scripts
├── vite.config.js           # Vite configuration
└── eslint.config.js         # ESLint configuration
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Dhineshkumar272005/E-Commerce.git
   cd E-Commerce
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open in your browser**

   Navigate to `http://localhost:5173` to view the app.

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server with hot module replacement |
| `npm run build` | Build the project for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint to check for code issues |

---

## 📖 Usage Guide

### Browsing Products
- The **Home** page displays all available products in a responsive grid
- Each product card shows the product image, name, and price
- Click **"View Details"** to see the full product description

### Shopping Cart
- Click **"Add to Cart"** on any product to add it to your cart
- The button shows the current quantity in parentheses (e.g., `Add to Cart (2)`)
- Navigate to the **Cart** page from the navbar to review your items
- Use the **+** / **−** buttons to adjust quantities
- Click **"Remove"** to delete an item from the cart

### Checkout
- Review your order summary with item-level and total pricing
- Click **"Place Order"** to complete your purchase

### Authentication
- Click **"Signup"** in the navbar to create a new account
- Click **"Login"** to sign in with existing credentials
- User sessions persist across page refreshes via localStorage

---

## 🧩 Architecture

The app follows a **component-based architecture** with React Context for state management:

- **`AuthContext`** — Manages user authentication (signup, login, logout) with localStorage persistence
- **`CartContext`** — Manages cart state (add, remove, update quantity, calculate totals)
- **React Router** — Handles client-side navigation between pages
- **React Hook Form** — Powers form validation on the authentication page

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/Dhineshkumar272005">Dhineshkumar</a>
</p>
