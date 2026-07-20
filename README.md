# Full Stack Food Delivery App

A full-stack food delivery application that allows users to browse restaurants, order meals, make secure payments, and track their orders in real time. The project is built with a modern technology stack featuring **React**, **Spring Boot**, **MongoDB**, and **AWS** to provide a scalable, secure, and production-ready solution.

---

## Overview

This application simulates a real-world food delivery platform with separate interfaces for customers and administrators. Customers can browse menus, add items to their cart, place orders, and track deliveries, while administrators can manage restaurants, menus, orders, and users.

The project demonstrates full-stack development concepts including REST APIs, authentication, cloud deployment, database management, and secure payment integration.

---

## Features

### Customer Features

- User registration and login
- JWT Authentication & Authorization
- Browse restaurants
- Search food by name or category
- Filter restaurants
- View food details
- Add items to cart
- Update cart quantity
- Secure checkout
- Online payment integration
- Place orders
- Order history
- Real-time order status tracking
- User profile management
- Responsive design

### Restaurant Admin Features

- Restaurant registration
- Restaurant dashboard
- Manage restaurant profile
- Add new menu items
- Edit menu items
- Delete menu items
- Manage food categories
- Upload food images
- Manage incoming orders
- Update order status
- View sales statistics

### Admin Features

- User management
- Restaurant approval
- Platform analytics
- Manage all orders
- Dashboard with reports

---

## Tech Stack

### Frontend

- React
- React Router
- Redux Toolkit / Context API
- Axios
- Material UI / Tailwind CSS
- Formik
- Yup

### Backend

- Java 21
- Spring Boot
- Spring Security
- Spring Data MongoDB
- JWT Authentication
- RESTful APIs
- Maven

### Database

- MongoDB
- MongoDB Atlas

### Cloud & DevOps

- AWS EC2
- AWS S3
- AWS IAM
- AWS CloudFront (Optional)
- Docker (Optional)

### Payment

- Stripe API

### Other Tools

- Git
- GitHub
- Postman
- IntelliJ IDEA
- VS Code

---

## System Architecture

```
React Frontend
       │
       │ REST API
       ▼
Spring Boot Backend
       │
       ├──────── MongoDB Atlas
       │
       ├──────── AWS S3
       │
       └──────── Stripe API
```

---

## Project Structure

```
food-delivery-app/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── context/
│   │   ├── redux/
│   │   ├── utils/
│   │   └── App.jsx
│   │
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   └── resources/
│   │   └── test/
│   │
│   ├── pom.xml
│   └── application.properties
│
└── README.md
```

---

## Database Collections

- Users
- Restaurants
- Categories
- Foods
- Cart
- Orders
- Payments
- Reviews

---

## Authentication

The application uses **JWT (JSON Web Tokens)** for secure authentication.

### User Roles

- Customer
- Restaurant Owner
- Admin

Protected routes ensure users can only access resources based on their assigned role.

---

## API Modules

### Authentication

- Register
- Login
- Logout

### Users

- Get Profile
- Update Profile

### Restaurants

- Create Restaurant
- Get Restaurants
- Update Restaurant
- Delete Restaurant

### Food

- Create Food Item
- Update Food Item
- Delete Food Item
- Get Food Items

### Cart

- Add Item
- Remove Item
- Update Quantity
- View Cart

### Orders

- Place Order
- Get Orders
- Update Status
- Cancel Order

### Payments

- Create Payment
- Verify Payment

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/food-delivery-app.git

cd food-delivery-app
```

---

## Backend Setup

### Prerequisites

- Java 21
- Maven
- MongoDB

Navigate to the backend folder.

```bash
cd backend
```

Install dependencies.

```bash
mvn clean install
```

Run the application.

```bash
mvn spring-boot:run
```

The backend will start on:

```
http://localhost:5454
```

---

## Frontend Setup

Navigate to the frontend folder.

```bash
cd frontend
```

Install dependencies.

```bash
npm install
```

Start the development server.

```bash
npm run dev
```

The frontend will run on:

```
http://localhost:5173
```

---

## Environment Variables

### Backend

Create an `.env` file or configure `application.properties`.

```properties
spring.data.mongodb.uri=

jwt.secret=

stripe.secret.key=

aws.access.key=

aws.secret.key=

aws.region=

aws.s3.bucket=
```

### Frontend

```env
VITE_API_URL=http://localhost:5454
VITE_STRIPE_PUBLISHABLE_KEY=
```

---

## Future Improvements

- Google Authentication
- Email verification
- Forgot password
- Restaurant ratings
- Customer reviews
- Coupons and discounts
- Push notifications
- Live order tracking with Google Maps
- Delivery partner application
- AI-powered food recommendations
- Progressive Web App (PWA)
- Dark mode

---

## Learning Objectives

This project demonstrates:

- Full Stack Development
- REST API Design
- Authentication with JWT
- Spring Security
- MongoDB Integration
- React State Management
- Cloud Deployment
- AWS Services
- Payment Gateway Integration
- Clean Architecture
- Responsive UI Design

---

## Screenshots

Add screenshots of the application here.

### Home Page

```
Screenshot Here
```

### Restaurant Page

```
Screenshot Here
```

### Cart

```
Screenshot Here
```

### Checkout

```
Screenshot Here
```

### Admin Dashboard

```
Screenshot Here
```

---

## Deployment

Frontend

- Vercel
- Netlify

Backend

- AWS EC2
- Render

Database

- MongoDB Atlas

Storage

- AWS S3

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License.

---

## Author

**Sheeba Kerubo**

GitHub: https://github.com/Sheeba193

Portfolio: *Add your portfolio link here*
