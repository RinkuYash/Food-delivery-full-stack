# Food-Delivery-App
A comprehensive web application built with React.js, Node.js, Express.js, and MongoDB, enabling users to browse, order, and manage food deliveries seamlessly.

# Features
User Authentication: Secure login and registration system.
Product Management: Admin interface to add, edit, and delete food items.
Shopping Cart: Add items to the cart and proceed to checkout.
Order Processing: Track order status from placement to delivery.
Payment Integration: Integrated with Stripe for secure payments.
# Tech Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Payment Gateway: Stripe
# Installation
1. Clone the Repository:

bash

git clone https://github.com/RinkuYash/food-delivery-app.git
cd food-delivery-app


2. Install Dependencies:

Backend:
bash

cd backend
npm install

Frontend:
bash

cd ../frontend
npm install

3. Configure Environment Variables:

Create a .env file in the backend directory with the following:
makefile

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key


4. Start the Application:

Backend:
bash

cd backend
npm start
Frontend:
bash

cd ../frontend
npm start


5. Access the Application:

Open your browser and navigate to http://localhost:3000.


# Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a pull request.
# License
This project is licensed under the MIT License.
