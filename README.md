# PLANTX
# Ecommerce Plant Website

This is an eCommerce website for selling plants, built using the MERN stack.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (signup, login, logout)
- Browse plants by categories
- Search functionality
- Add plants to cart
- Checkout process
- User profile management (view orders, update profile)
- Admin panel to manage products, orders, and users
- Responsive design for mobile and desktop

## Technologies Used

- **Frontend:**
  - React.js
  - Redux for state management
  - React Router for routing
  - Material-UI for UI components
  - Axios for HTTP requests

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB for database
  - Mongoose for MongoDB object modeling
  - JWT for authentication
  - bcryptjs for password hashing

## Screenshot
### Homepage
![Homepage](screenshot/Screenshot(129).png)
![Homepage](screenshot/Screenshot(131).png)

### Cart
![Cart](screenshot/Screenshot(135).png)

## Setup

1. **Clone the repository:**
   https://github.com/Nikhil2516/PLANTX.git
2. **Install dependencies:**
     npm i -y
     npm i nodemon
     cd client
     npm i -y
4. **Set up environment variables:**
  Create a `.env` file in the `backend` directory and add the following:
  PORT=8080
  MONGO_URL=""
  SECREATE=""

5. **Run the application:**
Start the backend server:
  npm run server
Start the frontend development server:
  cd client
  npm start


## Usage

- Visit `http://localhost:3000` to access the frontend of the website.
- For the admin panel, visit `http://localhost:3000/admin` and log in with admin credentials.
# PLANTX
