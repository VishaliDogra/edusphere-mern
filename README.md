# 🎓 EduSphere – Full Stack MERN Student Management System

EduSphere is a **Full-Stack Student Management System** built using the **MERN Stack**, designed to digitize and streamline academic and administrative operations of an educational institution.

It includes **secure authentication**, **role-based access**, **online fee payments**, **real-time chat**, **analytics dashboards**, and **notification services**, following real-world backend architecture and best practices.

---

## 🚀 Features

### 🔐 Authentication & Authorization

* JWT-based authentication
* Session management
* Role-based access control (Admin / Teacher / Student)
* Secure password hashing (bcrypt)
* Protected routes & middleware

---

### 👤 User Roles

* **Admin** – Full system control
* **Teacher** – Attendance, marks, communication
* **Student** – Profile, payments, performance tracking

---

### 📚 Student & Academic Management (CRUD)

* Student, teacher, and course management
* Attendance tracking (session-based)
* Marks & grade management
* Subject and class allocation

---

### 💬 Real-Time Chat (Socket.IO)

* Teacher ↔ Student one-to-one chat
* Secure socket connection using JWT
* Message history stored in MongoDB
* Online/offline user status

---

### 📊 Analytics Dashboard (Chart.js)

* Attendance trends
* Academic performance graphs
* Fee collection statistics
* Role-based dashboards

---

### 💰 Online Fee Payments (Stripe)

* Secure Stripe checkout
* Payment success & failure handling
* Payment history & invoices
* Email confirmation after payment

---

### 📲 Notifications

* **Twilio** – OTP login & SMS alerts
* **Nodemailer** – Email verification, fee receipts, result notifications

---

### 🛡️ Backend Validation & Security

* Input validation (Joi / express-validator)
* Centralized error handling
* Secure environment variables
* API response standardization

---

## 🧱 Tech Stack

### Frontend

* React.js
* React Router
* Chart.js
* Axios
* Context API

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Authentication & Security

* JWT (JSON Web Tokens)
* Sessions
* Bcrypt

### Third-Party Services

* Twilio (OTP & SMS)
* Nodemailer (Emails)
* Stripe (Payments)
* Socket.IO (Real-time chat)

---

## 🏗️ Project Architecture

```
Client (React)
   |
   | REST APIs / WebSockets
   |
Server (Node + Express)
   |
   | Mongoose
   |
Database (MongoDB)
```

---

## 📁 Folder Structure

```
edusphere-mern/
 ├── client/
 │   ├── components/
 │   ├── pages/
 │   ├── context/
 │   ├── services/
 │   └── hooks/
 │
 ├── server/
 │   ├── controllers/
 │   ├── models/
 │   ├── routes/
 │   ├── middlewares/
 │   ├── validations/
 │   ├── utils/
 │   └── app.js
 │
 ├── README.md
 └── .env.example
```

---

## 🔁 CRUD Operations Summary

| Module        | CRUD |
| ------------- | ---- |
| Users         | ✅    |
| Students      | ✅    |
| Teachers      | ✅    |
| Courses       | ✅    |
| Attendance    | ✅    |
| Marks         | ✅    |
| Payments      | ✅    |
| Chat Messages | ✅    |
| Notifications | ✅    |

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js
* MongoDB
* Stripe account
* Twilio account

---

### Clone the Repository

```bash
git clone https://github.com/your-username/edusphere-mern.git
cd edusphere-mern
```

---

### Backend Setup

```bash
cd server
npm install
npm run dev
```

---

### Frontend Setup

```bash
cd client
npm install
npm start
```

---

### Environment Variables (`.env`)

```
PORT=
MONGO_URI=
JWT_SECRET=
STRIPE_SECRET_KEY=
TWILIO_SID=
TWILIO_AUTH_TOKEN=
EMAIL_USER=
EMAIL_PASS=
```

---

## 🔮 Future Enhancements

* File uploads (assignments, profile images)
* Push notifications
* Video calling integration
* Mobile app (React Native)
* AI-based performance analytics

---

## 🎯 Learning Outcomes

* Real-world MERN architecture
* Secure authentication & authorization
* Payment gateway integration
* Real-time communication
* Data visualization
* Clean API & backend validation practices

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

---

## 📄 License

This project is for **learning and portfolio purposes**.

---

⭐ **If you like this project, consider giving it a star!**

