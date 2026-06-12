# Calorix – Healthcare & Heat Therapy E-Commerce Platform

## Overview

Calorix is a full-stack healthcare e-commerce platform designed for physiotherapy and heat-therapy products. The platform allows customers to browse products, place orders, submit reviews with images, and interact through a user-friendly interface.

The application provides a seamless shopping experience while enabling administrators to manage customer feedback and product-related interactions.

---

## Live Demo

🌐 Live Website: https://calorix-sigma.vercel.app/

---

## Features

### Customer Features

* Browse healthcare and heat-therapy products
* Responsive and mobile-friendly interface
* Shopping cart functionality
* WhatsApp-based ordering system
* Product reviews and ratings
* Image upload support for reviews
* Customer photo gallery
* Review statistics and rating breakdown
* FAQ section

### Admin Features

* Review moderation and management
* Access to customer-generated content
* Order tracking support

---

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6+)
* Bootstrap 5

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Cloud Services

* Cloudinary (Image Storage)

### Deployment

* Vercel (Frontend)
* Render (Backend)

### Other Tools

* Git
* GitHub
* Multer
* JWT Authentication
* Express Rate Limiting

---

## Project Structure

```bash
Calorix/
│
├── backend/
│   ├── models/
│   ├── uploads/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── images/
│
├── index.html
├── admin.html
├── belt.html
├── about.html
├── contact.html
├── style.css
└── README.md
```

---

## API Endpoints

### Reviews

#### Create Review

```http
POST /review
```

Uploads customer review, rating, and media.

#### Get Reviews

```http
GET /reviews
```

Returns all reviews and review statistics.

---

### Orders

#### Create Order

```http
POST /create-order
```

Creates a new customer order.

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Deepika-valikala/Calorix.git
cd Calorix
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Configure Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm start
```

### Run Frontend

Open `index.html`

or

```bash
python -m http.server 5500
```

Then visit:

```text
http://localhost:5500
```

---

## Future Improvements

* User Authentication
* Online Payment Gateway Integration
* Order History Tracking
* Product Inventory Management
* Admin Dashboard Analytics
* Email Notifications
* Wishlist Functionality
* Advanced Search & Filtering

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Full-Stack Web Development
* REST API Design
* MongoDB Database Management
* Cloudinary Media Storage
* Frontend UI/UX Development
* Deployment & Hosting
* Git Version Control
* Real-world Product Development

---

## Author

**Deepika Valikala**

* GitHub: https://github.com/Deepika-valikala
* LinkedIn: https://www.linkedin.com/in/deepika-valikala
* LeetCode: Deepika-231

---

## License

This project is developed for educational and portfolio purposes.
