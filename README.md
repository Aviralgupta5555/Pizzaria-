# 🍕 FastReact Pizzaria

FastReact Pizzaria is a **React-based restaurant management application** that streamlines the ordering process for customers. Users can log in, browse a dynamically loaded pizza menu, customize their orders, and track their order status.

## 🚀 Features

- 🔑 **User Login** – Customers log in using their name.
- 📜 **Dynamic Pizza Menu** – Menu items are fetched via an API.
- 🛒 **Order & Customize Pizzas** – Users can add multiple pizzas and customize them.
- 📍 **Order Placement** – Requires name, phone number, address, and GPS location.
- ⚡ **Priority Orders** – Users can pay **10% extra** to prioritize their orders.
- 📤 **Order Submission** – Orders are sent via a **POST request**.
- 💰 **Payment on Delivery** – Payments are handled offline upon delivery.
- 🔍 **Order Tracking** – Each user has a unique ID to check order status.

## 🛠 Tech Stack

- **Frontend:** React.js, React Router, Redux
- **Styling:** Tailwind CSS
- **Data Handling:** API calls (Fetch/Axios), Redux for state management

## 📦 Installation

Clone the repository and install dependencies:

```sh
git clone https://github.com/yourusername/FastReact-Pizzaria.git
cd FastReact-Pizzaria
npm install  # or yarn install
```

## ▶️ Running the Application

```sh
npm start  # or yarn start
```



## 📂 Project Structure

```
FastReact-Pizzaria/
│── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Main pages (Home, Menu, Orders, etc.)
│   ├── redux/             # Redux store and slices
│   ├── api/               # API handling functions
│   ├── App.js             # Main application component
│   ├── index.js           # Entry point
│   ├── styles/            # Tailwind CSS styles
│── public/                # Static assets
│── package.json           # Dependencies and scripts
```

## 🔥 Future Enhancements

- 🏷️ Coupon system for discounts
- 🌙 Dark mode support
- 📦 Order history and past order tracking

## 🤝 Contributing

Feel free to fork, raise issues, or submit pull requests!
