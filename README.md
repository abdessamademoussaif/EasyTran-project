🚗 Vehicle Booking Management System

A full-stack vehicle reservation and management platform built with a modern React frontend and a secure Node.js backend. The system allows users to browse vehicles, make bookings, manage accounts, and handle reservations in an intuitive interface designed for real-world fleet or rental management operations.

✨ Features
Frontend (React + Vite)

⚡ Vite for fast development and optimized builds

🎨 Tailwind CSS for modern, responsive UI

🧩 shadcn/ui for polished and reusable components

🔔 Notification system (toast)

🔐 Integration with backend authentication

🚘 Vehicle listing, details, and booking pages

📱 Fully responsive design

Backend (Node.js + Express.js)

📦 RESTful API architecture

🗄️ MongoDB with Mongoose for data modeling

🔐 Authentication using JWT + Passport.js

✉️ EmailJS for sending verification or notification emails

🚦 Route protection with middleware

🔄 CRUD operations for vehicles, users, and reservations

🛠️ Tech Stack
Frontend

React.js

Vite

Tailwind CSS

shadcn/ui

Axios

React Router

Backend

Node.js

Express.js

MongoDB / Mongoose

Passport.js

JSON Web Tokens (JWT)

EmailJS

Bcrypt

📂 Project Structure
/frontend
  📦frontend
 ┣ public
 ┣ src
 ┃ ┣ add-listing
 ┃ ┣ assets
 ┃ ┣ components
 ┃ ┣ lib
 ┃ ┣ listing-details
 ┃ ┣ profile-setting
 ┃ ┣ redux
 ┃ ┣ reservation-details
 ┃ ┣ Shared
 ┃ ┣ update-vehicle

/backend
 ┣ config
 ┣ middlewares
 ┣ models
 ┣ routes
 ┣ services
 ┣ uploads
 ┣ utils
 ┗ server.js

⚙️ Installation & Setup
1. Clone the repository
https://github.com/abdessamademoussaif/EasyTran-project
cd EasyTran-project

Frontend Setup

cd frontend

npm install

npm run dev

Backend Setup

cd backend

npm install

npm start


Create a .env file with:

MONGO_URI=your_mongo_connection

JWT_SECRET=your_secret_key

EMAILJS_KEY=your_key

EMAILJS_TEMPLATE=your_template

EMAILJS_SERVICE=your_service

🚀 Deployment

Both frontend and backend are structured for deployment on platforms like:

Vercel

Netlify

Render

Railway

AWS / DigitalOcean

📸 Screenshots


📜 License

This project is licensed under the MIT License.
