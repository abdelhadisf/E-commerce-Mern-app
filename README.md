# 🛒 Buy-it – E-commerce Web Application

A full-stack e-commerce platform built with the **MERN stack** (MongoDB, Express.js, React, Node.js) that allows users to **browse, search, and purchase** products online. Includes **secure authentication**, **admin panel**, and **payment integration**.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- User registration and login
- JWT-based authentication
- Password encryption (bcrypt)
- Protected routes (user/admin)

### 🛍️ Product Management
- Browse by category
- Advanced search & filtering
- Product details with image preview
- Admin product CRUD operations
- Inventory control

### 🛒 Shopping Cart & Checkout
- Add/remove/update cart items
- Persistent cart per user
- Secure checkout flow
- Order history & tracking

### 💳 Payment Integration
- Stripe & PayPal support
- Secure payment processing
- Email receipts & order confirmation

### 🛠️ Admin Panel
- Manage products & orders
- Manage users & roles
- Basic sales analytics

---

## 🧰 Tech Stack

### Frontend
- `React.js`
- `Redux` (state management)
- `React Router` (routing)
- `Axios` (HTTP requests)
- `Bootstrap` / `Material-UI` (styling)

### Backend
- `Node.js`
- `Express.js`
- `MongoDB` + `Mongoose`
- `JWT` (auth)
- `bcrypt` (password hashing)

### Other Tools
- `Multer` (file uploads)
- `Nodemailer` (email service)
- `Stripe` / `PayPal` (payments)

---

## ⚙️ Installation & Setup

### 🔧 Prerequisites
- Node.js (v14+)
- MongoDB (local or cloud)
- npm or yarn

---

### 🖥️ Backend Setup

```bash
git clone https://github.com/abdelhadisf/E-commerce-Mern-app.git
cd E-commerce-Mern-app/backend
npm install
```

#### Create `.env` in `/backend`:
```
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
EMAIL_HOST=your_email_host
EMAIL_PORT=587
EMAIL_USER=your_email
EMAIL_PASS=your_password
```

#### Run Backend:
```bash
npm run dev
```

---

### 💻 Frontend Setup

```bash
cd ../frontend
npm install
```

#### Create `.env` in `/frontend`:
```
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

#### Run Frontend:
```bash
npm start
```

---

## 🔧 Usage Flow

1. **Register / Login**
2. **Browse or Search Products**
3. **Add to Cart**
4. **Secure Checkout**
5. **View Order History**

---

## 📱 API Endpoints

### Auth
| Method | Endpoint                | Description         |
|--------|-------------------------|---------------------|
| POST   | `/api/auth/register`    | Register a new user |
| POST   | `/api/auth/login`       | User login          |
| GET    | `/api/auth/profile`     | Get user profile    |

### Products
| Method | Endpoint                  | Description          |
|--------|---------------------------|----------------------|
| GET    | `/api/products`           | List all products    |
| GET    | `/api/products/:id`       | Get product by ID    |
| POST   | `/api/products`           | Create product (admin) |
| PUT    | `/api/products/:id`       | Update product (admin) |
| DELETE | `/api/products/:id`       | Delete product (admin) |

### Orders
| Method | Endpoint                    | Description             |
|--------|-----------------------------|-------------------------|
| POST   | `/api/orders`               | Create new order        |
| GET    | `/api/orders/myorders`      | Get user’s orders       |
| GET    | `/api/orders/:id`           | Get order by ID         |

---

## 👥 Contributing

1. Fork this repo
2. Create your feature branch: `git checkout -b feature/MyFeature`
3. Commit your changes: `git commit -m "Add MyFeature"`
4. Push to the branch: `git push origin feature/MyFeature`
5. Open a Pull Request

---

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## 👤 Author

**Soufi Merzoug Abdelhadi**  
GitHub: [@abdelhadisf](https://github.com/abdelhadisf)  
LinkedIn: [Your LinkedIn URL]

---

## 🙏 Acknowledgments

- MERN Stack community
- Inspiration from real e-commerce platforms
- All testers & contributors

---

## 📬 Support

For issues or questions, open a GitHub issue or contact the author directly.
