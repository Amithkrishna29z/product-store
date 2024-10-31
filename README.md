# Product Store

Product Store is a full-stack application that allows users to manage products. Built with Express and MongoDB for the backend and React (or similar) for the frontend, the app includes essential features for creating, reading, updating, and deleting (CRUD) product data.

## Features

- **Backend**: Node.js, Express, MongoDB with Mongoose ODM for data management.
- **Frontend**: (Specify if using React, Vue, etc.) with a responsive UI to display and interact with products.
- **Data Storage**: Stores product information, including name, price, image, and created date.
- **RESTful API**: Provides endpoints for product operations (add, fetch, delete, update).
- **State Management**: Uses Zustand to manage and share product data across the app.

## Getting Started

### Prerequisites

- **Node.js**: Ensure Node.js and npm are installed.
- **MongoDB**: MongoDB server (local or cloud, e.g., MongoDB Atlas) configured.

### Installation

1. **Clone the repository**:
   
   git clone https://github.com/yourusername/product-store.git

2. **Install dependencies**:

    npm install

3. **Set up environment variables**:

    Create a .env file in the root directory for sensitive information, like the MongoDB URI.

4. **Run the backend**:

    npm run dev

5. **Build and run frontend**:

    npm run build

### Scripts

- **npm run dev**:  Starts backend in development mode with nodemon.
- **npm run build**:  Installs frontend dependencies and builds the frontend.
- **npm start**:   Starts backend in production mode.


### API Endpoints

- **GET /api/products:**: Fetch all products.
- **POST /api/products:**: Add a new product.
- **PUT /api/products/**: Update a product by ID.
- **DELETE /api/products/**: Delete a product by ID.


### Technologies

- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Frontend**: Chakra UI (or another styling library), Zustand (for state management)
- **Dev Tools**: Nodemon, cross-env