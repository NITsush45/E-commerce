# E-Commerce Platform

An e-commerce web application built performing CRUD operations in backend and filtering, searcging in the frontend according to the user requiremnets.

## Features

- User authentication and authorization
- Product browsing and filtering
- Order management
- Performs CRUD(CREATE, READ, UPDATE, DELETE) opeartions using Postman in the BackEnd

## Tech Stack

- **Frontend**: React, CSS, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Git, npm, dotenv

## Folder Structure
e-commerce/
├── e-commerce-frontend/
│   ├── config/
│   ├── database.js
│   ├── controller/
│   │   └── productController.js
│   ├── models/
│   │   └── Product.js
│   ├── routes/
│   │   └── productRoutes.js
│   ├── node_modules/
│   ├── dotenv
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
├── e-commerce-backend/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/
│   │   │   ├── ProductCard.jsx
│   │   │   └── SearchFilters.jsx
│   │   ├── App.js
│   │   └── App.css
│   ├── node_modules/
│   ├── .gitignore
│   ├── package.json
│   └── package-lock.json
├── node_modules/
├── package.json
└── README.md

## Installation and Setup

### Prerequisites

Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Postman](https://www.postman.com/)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NITsush45/E-commerce.git
   cd e-commerce
### Set-Up BackEnd
cd e-commerce-backend
npm install
npm run dev

###Set Up FrontEnd
cd ../e-commerce-frontend
npm install
npm start

###To run both concurrently
Add
"start": "concurrently \"npm --prefix ./e-commerce-backend start\" \"npm --prefix ./e-commerce-frontend start\""
in root package.json file in "scripts".

### Access the App:

Frontend: Visit http://localhost:3001 in your browser.
Backend: Runs on http://localhost:5000 by default.

###Using Postman for CRUD Operations:-
Open Postman and create a new collection.

Use the following routes to interact with the MongoDB database:

Create: POST http://localhost:5000/api/products
Make raw JSON file and POST
Add a new resource to the database.

Read: GET http://localhost:5000/api/products
Fetch all resources or a single resource by ID.

Update: PUT http://localhost:5000/api/products/:id
Update a specific resource by its ID.

Delete: [DELETE http://localhost:5000/api/products/:id
Remove a specific resource by its ID.

Send requests and view responses directly in Postman.
###Create a .env file in the e-commerce-backend folder with the following:
MONGO_URI=MONGO_URI="mongodb+srv://sushiitantmi45:ipvhwvGQbP3n4IMV@cluster0.3ok3p.mongodb.net/?retryWrites=true&w=majority"

###Contact
For any inquiries, reach out at:

Email: sushiitantmi45@gmail.com
GitHub: https://github.com/NITsush45

      

