# Product Store

Product Store is a full-stack MERN (MongoDB, Express, React, Node.js) application for managing product listings with CRUD (Create, Read, Update, Delete) operations. The project includes a responsive frontend built with React and Chakra UI, and a backend powered by Node.js, Express, and MongoDB.

## Features

- Create, read, update, and delete products.
- Responsive design with Chakra UI.
- State management using Zustand.
- Backend API with Express and MongoDB.
- Environment-based configuration for development and production.

## Technologies Used

- **Frontend**: React, Chakra UI, Zustand, Vite
- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Build Tools**: Vite, ESLint

## Installation

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB instance running (local or cloud).

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/product-store.git
   cd product-store/backend
2. Install backend dependencies:
   ```sh
   npm install
3. Set up environment variables: Create a `.env` file in the `backend` directory and add the following:
   ```sh
   MONGO_URI=your_mongodb_connection_string
   NODE_ENV=development
4. Start the backend server:
   ```sh
   npm run dev
### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
2. Install frontend dependencies:
   ```sh
   npm install
3. Start the frontend development server:
   ```sh
   npm run dev

