# Buy-it - E-commerce Web Application

A full-stack e-commerce platform built with the MERN stack (MongoDB, Express.js, React, Node.js) that allows users to browse, search, and purchase products online with secure authentication and payment integration.

## 🚀 Features

- **User Authentication & Authorization**
  - User registration and login
  - JWT-based authentication
  - Password encryption with bcrypt
  - Protected routes

- **Product Management**
  - Browse products by categories
  - Advanced search and filtering
  - Product details with images
  - Inventory management

- **Shopping Cart & Checkout**
  - Add/remove items from cart
  - Update quantities
  - Secure checkout process
  - Order history tracking

- **Payment Integration**
  - Secure payment processing
  - Multiple payment methods support
  - Order confirmation and receipts

- **Admin Panel**
  - Product management (CRUD operations)
  - Order management
  - User administration
  - Sales analytics

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Redux for state management
- React Router for navigation
- Axios for API calls
- Bootstrap/Material-UI for styling

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing

**Additional Tools:**
- Multer for file uploads
- Nodemailer for email services
- Stripe/PayPal for payments

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Backend Setup

1. Clone the repository
```bash
git clone https://github.com/abdelhadisf/E-commerce-Mern-app.git
cd E-commerce-Mern-app

Install backend dependencies

cd backend
npm install
Create a .env file in the backend directory:

NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
EMAIL_HOST=your_email_host
EMAIL_PORT=587
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
Start the backend server

npm run dev
Frontend Setup
Install frontend dependencies

cd frontend
npm install
Create a .env file in the frontend directory:

REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
Start the frontend application

npm start
🔧 Usage
User Registration/Login: Create an account or login with existing credentials
Browse Products: Navigate through different product categories
Search & Filter: Use search functionality to find specific products
Add to Cart: Select products and add them to your shopping cart
Checkout: Complete the purchase with secure payment processing
Order Tracking: View order history and track shipments
📱 API Endpoints
Authentication
POST /api/auth/register - User registration
POST /api/auth/login - User login
GET /api/auth/profile - Get user profile
Products
GET /api/products - Get all products
GET /api/products/:id - Get product by ID
POST /api/products - Create product (Admin)
PUT /api/products/:id - Update product (Admin)
DELETE /api/products/:id - Delete product (Admin)
Orders
POST /api/orders - Create new order
GET /api/orders/myorders - Get user orders
GET /api/orders/:id - Get order by ID
🤝 Contributing
Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

👤 Author
Soufi Merzoug Abdelhadi

GitHub: @abdelhadisf
LinkedIn: [Your LinkedIn Profile]
🙏 Acknowledgments
Thanks to the MERN stack community for excellent documentation
Inspiration from various e-commerce platforms
Special thanks to contributors and testers
📞 Support
If you have any questions or need help, please open an issue or contact me directly.
