# 🌿 Paradise Nursery Shopping

A responsive React application that simulates an online plant nursery where users can browse houseplants, add them to a shopping cart, manage quantities, and view their order summary.

This project was developed as part of the **IBM Developing Front-End Apps with React** course and demonstrates the use of **React**, **Redux Toolkit**, **React Hooks**, and **GitHub Pages** for deployment.

## 🚀 Live Demo

**Application:**
https://ncontrerass.github.io/e-plantShopping/

## 📸 Features

* Landing page with company introduction
* Product catalog organized by plant categories
* Add products to the shopping cart
* Prevent duplicate cart entries by increasing quantity
* Increase or decrease item quantities
* Remove items from the cart
* Dynamic shopping cart badge showing the total number of items
* Automatic calculation of:

  * Total cost per product
  * Total order amount
* Continue Shopping navigation
* Responsive layout for desktop and mobile devices
* Deployed using GitHub Pages

## 🛠️ Technologies Used

* React
* Redux Toolkit
* JavaScript (ES6+)
* HTML5
* CSS3
* Vite
* Git
* GitHub
* GitHub Pages

## 📂 Project Structure

```text
src/
│
├── App.jsx
├── ProductList.jsx
├── CartItem.jsx
├── CartSlice.jsx
├── AboutUs.jsx
├── App.css
├── ProductList.css
├── AboutUs.css
└── CartItem.css
```

## 🛒 Shopping Cart Functionality

The application uses **Redux Toolkit** to manage the shopping cart state.

Implemented actions include:

* **addItem**

  * Adds a plant to the cart.
  * If the plant already exists, its quantity is incremented.

* **updateQuantity**

  * Updates the quantity of an existing item.

* **removeItem**

  * Removes a product completely from the cart.

The shopping cart icon dynamically displays the total quantity of products currently in the cart.

## ▶️ Running the Project Locally

Clone the repository:

```bash
git clone https://github.com/ncontrerass/e-plantShopping.git
```

Navigate to the project:

```bash
cd e-plantShopping
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open your browser at:

```
http://localhost:5173
```

## 📦 Production Build

Generate a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## 🚀 Deployment

The application is automatically deployed to **GitHub Pages** using **GitHub Actions** whenever changes are pushed to the `main` branch. GitHub Pages supports publishing built static sites through Actions workflows.

## 📚 What I Learned

This project strengthened my understanding of:

* React functional components
* React Hooks (`useState`, `useSelector`, `useDispatch`)
* Redux Toolkit state management
* Component communication
* Conditional rendering
* Event handling
* Dynamic UI updates
* Responsive CSS layouts
* GitHub Actions
* GitHub Pages deployment

## 📄 License

This project is intended for educational purposes as part of the IBM Front-End Development course.
