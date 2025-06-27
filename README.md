# E-pharma – Pharmacy Management Application

This is a full-stack E-Pharmacy Web Application designed to streamline pharmacy operations, enable online purchases, and offer healthcare services like appointment booking. It combines both user and admin features in a seamless, responsive interface.

## ✨ Features
- User-friendly UI for browsing and purchasing products
- Category-based listings (Dermatology, Dental, Women's Health, etc.)
- Doctor and nurse appointment booking
- Admin dashboard for managing products
- Integrated shopping cart and Stripe payment gateway
- User authentication for patients, doctors, and nurses
- Responsive design for mobile and desktop

## 🛠 Tech Stack
- *Frontend:* React, Redux, Styled Components, React Router
- *Backend:* Node.js, Express.js, MongoDB, Mongoose
- *Other:* Multer for file uploads, dotenv for env vars, Stripe for payments

## 📁 Folder Structure
E-pharma/
├── backend/
│ ├── config/
│ ├── controller/
│ ├── data/
│ ├── models/
│ ├── routes/
│ └── seederScript.js
├── frontend/
│ ├── public/
│ ├── src/
│ └── package.json
├── uploads/
├── .env
├── Procfile
└── server.js

bash
Copy code

## 🚀 Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB running locally (mongodb://localhost:27017/)

### Installation
1. Clone the repo:
   ```sh
   git clone https://github.com/shashi1415/E-pharma.git
   cd E-pharma
Backend setup:

sh
Copy code
cd backend
npm install
Frontend setup:

sh
Copy code
cd ../frontend
npm install
Create a .env file in backend/:

env
Copy code
MONGO_URI=mongodb://localhost:27017/
PORT=5000
Running the Application
Start backend:

sh
Copy code
npm run start:dev
Start frontend:

sh
Copy code
cd frontend
npm start
Backend: http://localhost:5000

Frontend: http://localhost:3000

Seeding the Database
sh
Copy code
npm run data:import
Deployment
Can be deployed via Heroku, Vercel, or Netlify.

Procfile included for Heroku deployment.

📚 Learn More
React

Express

MongoDB

Stripe