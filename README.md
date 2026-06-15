# 🏥 MediCare - Hospital Management System

<div align="center">

# 🏥 MediCare

### A Modern MERN Stack Hospital Management System

A complete Hospital Management System built using the MERN Stack for managing patients, doctors, appointments, prescriptions, billing, and administrative operations.

🌐 **Live Demo:** https://medicare-frontend-kyt9.onrender.com

![React](https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge\&logo=express\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)

</div>

---

# 📖 About

MediCare is a comprehensive Hospital Management System designed to digitalize healthcare services and improve hospital operations. The application provides dedicated dashboards for Patients, Doctors, and Administrators to manage appointments, prescriptions, medical records, and billing efficiently.

---

# ✨ Features

## 👨‍⚕️ Doctor Module

* Doctor Registration
* Doctor Login
* Manage Appointments
* View Patient Records
* Generate Prescriptions
* Dashboard Management

## 🧑 Patient Module

* Patient Registration
* Secure Login
* Book Appointments
* Cancel Appointments
* View Medical History
* Download Prescriptions
* Billing Information

## 👨‍💼 Admin Module

* Admin Login
* Manage Doctors
* Manage Patients
* Manage Appointments
* Billing Management
* Dashboard Analytics

---

# 🚀 Tech Stack

| Frontend | Backend            | Database      |
| -------- | ------------------ | ------------- |
| React.js | Node.js            | MongoDB       |
| HTML5    | Express.js         | Mongoose      |
| CSS3     | JWT Authentication | MongoDB Atlas |

---

# 🏗️ System Architecture

```
Patient
Doctor
Admin
   │
   ▼
React.js Frontend
   │
   ▼
Node.js + Express.js
   │
   ▼
MongoDB Database
   │
   ▼
Application Response
```

---

# 📂 Project Structure

```
MediCare/

├── frontend/
│   ├── public/
│   ├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── App.jsx
│   └── main.jsx
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── server.js
│   └── package.json
│
├── screenshots/
│   ├── home.png
│   ├── login.png
│   ├── patient-dashboard.png
│   ├── doctor-dashboard.png
│   ├── admin-dashboard.png
│   ├── appointment.png
│   ├── prescription.png
│   └── billing.png
│
├── README.md
├── .gitignore
└── package.json
```

---

```

---

# 🔐 Authentication

* JWT Authentication
* Protected Routes
* Role Based Access
* Secure Password Management

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Pratiksha0516/MediCare.git
```

```
cd MediCare
```

---

## Install Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## Install Backend

```bash
cd backend

npm install

npm start
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY
```

---

# 📊 Main Modules

* Authentication
* Patient Management
* Doctor Management
* Appointment Scheduling
* Prescription Management
* Medical Records
* Billing Management
* Payment Management
* Admin Dashboard

---

# 📡 REST APIs

## Authentication

```
POST /register

POST /login

POST /logout
```

## Patients

```
GET /patients

POST /patients

PUT /patients

DELETE /patients
```

## Doctors

```
GET /doctors

POST /doctors

PUT /doctors

DELETE /doctors
```

## Appointments

```
GET /appointments

POST /appointments

PUT /appointments

DELETE /appointments
```

---

# 🧪 Testing

The system includes:

* Unit Testing
* Integration Testing
* System Testing
* Database Testing
* Security Testing
* Performance Testing
* Compatibility Testing
* Acceptance Testing

---

# 🚀 Future Enhancements

* Video Consultation
* AI Healthcare Assistant
* Online Payment Gateway
* SMS Notifications
* Email Notifications
* Electronic Health Records
* Mobile Application
* Analytics Dashboard

---

# 🤝 Contributing

Fork the repository.

Create a new branch.

```bash
git checkout -b feature-name
```

Commit changes.

```bash
git commit -m "Added new feature"
```

Push changes.

```bash
git push origin feature-name
```

Create a Pull Request.

---

# 👩‍💻 Developer

## Pratiksha

### MERN Stack Developer

GitHub:

https://github.com/Pratiksha0516

Live Project:

https://medicare-frontend-kyt9.onrender.com

---

# 📜 License

This project is developed for educational and learning purposes.

---

<div align="center">

## ⭐ Star this repository if you like this project!

### ❤️ Thank You for Visiting!

Built with React.js, Node.js, Express.js, and MongoDB.

</div>
