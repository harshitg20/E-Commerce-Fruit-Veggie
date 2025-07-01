# 🍎 Mini E-commerce App - Fruits & Vegetables

This is a simple and intuitive mini e-commerce application specifically designed for fruit and vegetable sellers. Built using **ReactJS**, this project demonstrates core functionalities of a modern online shopping experience including user authentication, product listing, cart management, and clean component architecture.

---

## 🚀 Features

### 1. 👤 User Authentication
- **Login Page**: Existing users can log in using credentials.
- **Signup Page**: New users can register with necessary details.

### 2. 🛒 Product Listing
- **Browse Products**: Users can view all available fruits and vegetables after logging in.
- **Product Details**: Each product includes a detailed view with description, price, and "Add to Cart" option.

### 3. 🧺 Cart Management
- **Add to Cart**: Users can add products to their cart.
- **View Cart**: Users can view and manage cart items with quantity controls.

---

## 🧱 Project Structure

### 🔹 Components
- **Login** – Handles user login.
- **Signup** – Handles new user registration.
- **ProductList** – Displays the available products.
- **ProductDetails** – Shows details of a selected product.
- **Cart** – Displays and manages items in the cart.

### 🔹 Pages
- **Home** – Landing page with product listings.
- **Login** – User login page.
- **Signup** – User signup page.
- **Cart** – Shopping cart page.

### 🔹 Services
- **AuthService** – Manages API requests related to authentication.
- **ProductService** – Fetches product data from backend or mock API.
- **CartService** – Manages cart-related operations.

### 🔹 State Management
- **Context API or Redux** – Used to manage global state:
  - User Authentication Status
  - Cart Items

---

## 🛠️ Tech Stack

- **Frontend**: ReactJS (with Hooks, Context API or Redux)
- **Styling**: CSS / TailwindCSS / Bootstrap (choose as needed)
- **Routing**: React Router
- **State Management**: Context API / Redux
- **API Calls**: Axios / Fetch

---

## 📦 Installation & Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/fruit-veggie-store.git

# Navigate to the project directory
cd fruitveggie

# Install dependencies
npm install

# Start the development server
npm run dev
