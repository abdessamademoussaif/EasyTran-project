# - Vehicle Booking Management System

A full-stack platform for managing and booking vehicles. The system allows users to browse available vehicles, view details, make reservations, and manage their accounts. Administrators can manage vehicles, users, and bookings through a secure dashboard.

---

## - Description

This project consists of a **React + Vite frontend** and a **Node.js + Express + MongoDB backend**.  
It includes user authentication with JWT & Passport.js, responsive UI with Tailwind CSS and shadcn/ui, and email support via EmailJS.

The system is built to be fast, scalable, and suitable for real-world fleet or rental management use cases.

---

## - Getting Started

### - Dependencies

#### **Frontend**
- Node.js 18+
- npm or pnpm
- Modern browser

#### **Backend**
- Node.js 18+
- MongoDB database 
- EmailJS account (for email services)

---

## - Installing

### **Clone the project**
```bash
git clone https://github.com/abdessamademoussaif/EasyTran-project.git 
cd EasyTran-project
```

---

## - Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## - Backend Setup

```bash
cd backend
npm install
npm start
```

### **Environment Variables**

Create a `.env` file inside `/backend`:

```
MONGO_URI=your_mongo_connection
JWT_SECRET=your_jwt_secret
EMAILJS_USER=your_emailjs_user_id
EMAILJS_SERVICE=your_emailjs_service_id
EMAILJS_TEMPLATE=your_emailjs_template_id
```

---

## - Executing Program

### **Start Frontend**
```bash
npm run dev
```

### **Start Backend**
```bash
npm start
```

Access the app in your browser:  
```
http://localhost:5173
```

Backend API runs on:  
```
http://localhost:5000
```

---

## - Help

Common issues:

### **MongoDB connection error**
Check:
```
MONGO_URI in .env
```
Ensure your IP is whitelisted if using MongoDB Atlas.

### **CORS issues**
Make sure the backend has:
```js
app.use(cors({ origin: "http://localhost:5173", credentials: true }));
```

### **Email not sending**
Verify your EmailJS keys and template.

---

## - Authors

**Abdessamade Moussaif**  
GitHub: https://github.com/abdessamademoussaif
E-mail: abdessamademoussaif@gmail.com


---

## - License

This project is licensed under the **MIT License** — see the LICENSE file for details.

---

## - Acknowledgments

Thanks to the creators of tools and libraries used in this project:

- React  
- Vite  
- Tailwind CSS  
- shadcn/ui  
- Express.js  
- MongoDB  
- JWT  
- Passport.js  
- EmailJS  
