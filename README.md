# final-project-Paradise-Nursery
# Paradise Nursery - Shopping Application

Welcome to **Paradise Nursery**, a high-performance e-commerce web application specialized in offering a diverse range of unique houseplants. This project was built to provide a seamless shopping experience, from browsing exotic greenery to managing a dynamic shopping cart.

## 🌿 Project Overview
Paradise Nursery is a React-based application that utilizes modern web development practices to create a user-friendly interface for plant enthusiasts. Users can explore various categories of plants, view detailed pricing, and manage their selections in real-time.

## 🚀 Key Features
* **Interactive Landing Page:** A visually appealing entrance with a "Get Started" call-to-action.
* **Dynamic Product Listing:** Plants categorized by type (e.g., Air Purifying, Low Maintenance) with real-time "Add to Cart" functionality.
* **State Management with Redux:** Centralized state handling for cart additions, removals, and quantity updates using Redux Toolkit.
* **Responsive Shopping Cart:** * Automatic calculation of total costs per item.
    * Grand total calculation for the entire order.
    * Interactive controls to increase, decrease, or delete items.
* **Seamless Navigation:** A persistent navbar for easy switching between the store and the cart.

## 🛠️ Tech Stack
* **Frontend:** React.js (Vite)
* **State Management:** Redux Toolkit
* **Styling:** CSS3 (Custom animations and responsive grid layouts)
* **Icons:** FontAwesome / React Icons

## 📂 Project Structure
* `src/components/`: Contains reusable UI components like `ProductList`, `CartItem`, and `AboutUs`.
* `src/store/`: Contains the Redux store configuration and the `CartSlice`.
* `src/App.jsx`: The main entry point handling view toggling between the landing page and the shop.

## 📖 How to Run Locally
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/deolyneast-ship-it/paradise-nursery.git](https://github.com/deolyneast-ship-it/paradise-nursery.git)
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the development server:**
    ```bash
    npm run dev
    ```

---
*Developed as part of the IBM Front-End Developer Professional Certificate.*
