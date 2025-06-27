# E-pharma
# Medi-Mitra E-Pharmacy Application

This project is a full-stack e-pharmacy web application called **Medi-Mitra**. It provides users with a seamless experience to browse, purchase, and learn about healthcare products and services online.

## Features
- User-friendly interface for browsing and searching products
- Shopping cart and checkout functionality
- Category-based product listings (Dermatology, Dental, Women's Health, etc.)
- Doctor and nurse appointment booking
- Contact and About pages
- Responsive design for mobile and desktop
- Admin features for managing products
- Integrated payment gateway (Stripe)

## Tech Stack
- **Frontend:** React, Redux, Styled Components, React Router
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Other:** Stripe for payments, Multer for file uploads, dotenv for environment variables

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running locally (default: `mongodb://localhost:27017/`)

### Installation
1. Clone the repository:
   ```
   git clone <repo-url>
   cd Pharmacy-
   ```
2. Install backend dependencies:
   ```
   npm install
   ```
3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   cd ..
   ```
4. Set up your `.env` file in the `backend/` directory:
   ```
   MONGO_URI=mongodb://localhost:27017/
   PORT=5000
   ```

### Running the Application
- To start the backend server:
  ```
  npm run start:dev
  ```
- To start the frontend React app:
  ```
  cd frontend
  npm start
  ```
- The backend runs on [http://localhost:5000](http://localhost:5000)
- The frontend runs on [http://localhost:3000](http://localhost:3000)

### Seeding the Database
To import sample product data:
```
npm run data:import
```

## Folder Structure
- `backend/` - Node.js/Express API, models, controllers, routes
- `frontend/` - React app source code

## Learn More
- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React documentation](https://reactjs.org/)
- [Express documentation](https://expressjs.com/)
- [MongoDB documentation](https://docs.mongodb.com/)

---

© 2025 Medi-Mitra. All rights reserved.
