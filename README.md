# FakeStoreAppV2

My fake store app is a simple e-commerce demo built with modern React tools. It uses the FakeStoreAPI to fetch product and category data, allows users to browse products, filter by category, add items to a shopping cart, and simulate a checkout. The cart state is managed with Redux Toolkit and persists in sessionStorage so that it survives page refreshes!!

---

## Features

- **Product Catalog**  
  - Fetches all products from FakeStoreAPI using React Query.  
  - Displays product image, title, price, category, rating, and a brief description.  
  - “Details” button on each product card (placeholder for future detailed view).  
  - “Add to Cart” button that dispatches a Redux action.

- **Category Filter**  
  - Retrieves available categories from FakeStoreAPI.  
  - Dynamically populates a dropdown so users can filter products by category.

- **Shopping Cart**  
  - Managed with Redux Toolkit (cart slice) for add, remove, update quantity, and clear cart.  
  - Cart contents persist to sessionStorage on every change.  
  - Cart page shows all items with image, title, unit price, quantity input, subtotal, and a remove button.  
  - Displays total item count and total price.  
  - “Checkout” button clears the cart and gives feedback.

- **Responsive Navbar**  
  - Styled with React Bootstrap (dark background, white text).  
  - Links to Home, Products (placeholder), Add Product (placeholder), and Cart (with live item count).  
  - Collapses into a hamburger menu on smaller screens.

---

## Tech Stack

- **React** (v18)  
- **Vite** (v4) for development server and build.  
- **Redux Toolkit** (v2.x) for state management (cart slice).  
- **React Redux** (v8.x) to connect Redux to React components.  
- **React Query** (v5.x) for data fetching and caching.  
- **React Router DOM** (v6.x) for client-side routing.  
- **React Bootstrap** (v2.x) & **Bootstrap** (v5.x) for UI components.  
- **Axios** (v1.x) for HTTP requests to FakeStoreAPI.  
- **ESLint** (v9.x) with `eslint-plugin-react` and `eslint-plugin-react-hooks` for linting.  
- **TypeScript** (v5.x) support in the codebase.

---

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/dielac/FakeStore_App.git
   cd FakeStore_App

