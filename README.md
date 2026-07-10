# ⚡ ElectroHub

ElectroHub is a full-stack e-commerce web application for electronic products. It provides a modern shopping experience with a responsive React frontend and a Node.js + Express backend powered by MongoDB.

## ✨ Features

- 🛒 Browse electronic products
- 🔍 Search products
- 👤 User authentication
- ❤️ Wishlist functionality
- 🛍️ Shopping cart
- 📦 Product details page
- 📱 Responsive UI
- ⚡ Fast and intuitive user experience

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Tools
- Git
- Docker

---

## 📂 Project Structure

```
ElectroHub
│
├── backend
│  ├── server.js
│  ├── package.json
│  └── .env
│
├── electrohub
│   ├── public
│   ├── src
│   ├── package.json
│   ├── vite.config.js
│   └── index.html
│
├── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ramaprasadnayak/ElectroHub.git
cd ElectroHub
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend

```bash
npm start
```

The backend runs on

```
http://localhost:5000
```

---

## Frontend Setup

Open another terminal.

```bash
cd electrohub
npm install
npm run dev
```

The frontend runs on

```
http://localhost:5173
```

---

## 🐳 Docker

```bash
docker-compose up --build
```

---

## 📸 Screenshots

![image alt](https://github.com/Ramaprasadnayak/Electrohub/blob/a7105cdd00d327062f133c8d881fb3b1c7fa626f/home.png)
![image alt](https://github.com/Ramaprasadnayak/Electrohub/blob/a7105cdd00d327062f133c8d881fb3b1c7fa626f/login.png)
![image alt](https://github.com/Ramaprasadnayak/Electrohub/blob/a7105cdd00d327062f133c8d881fb3b1c7fa626f/productpage.png)
![image alt](https://github.com/Ramaprasadnayak/Electrohub/blob/a7105cdd00d327062f133c8d881fb3b1c7fa626f/cart.png)
![image alt](https://github.com/Ramaprasadnayak/Electrohub/blob/a7105cdd00d327062f133c8d881fb3b1c7fa626f/products.png)

---

## 🔮 Future Improvements

- AI-based product recommendations
- Payment gateway integration
- Order tracking
- Admin dashboard
- Product reviews and ratings
- Email notifications

---

## 👨‍💻 Developers

Developed by a team of 2.

---

## 📄 License

This project is for educational purposes.
