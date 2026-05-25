# Eventora

🔗 Live Demo:[https://eventora-mern-ivbf.onrender.com]

---

# Eventora - Full Stack Event Booking Platform

Eventora is a full-stack MERN application that allows users to browse, register, and book events securely using OTP verification and role-based authentication.

The platform supports both free and paid events with admin approval workflows, secure booking management, analytics dashboard, and email notifications.

---

# Features

## Authentication & Security

- JWT Authentication
- Password Hashing using bcrypt
- OTP-based Email Verification
- Secure Login System
- Role-Based Authorization

---

## User Features

- User Registration & Login
- Email OTP Verification
- Browse Events
- Book Event Tickets
- View Booking Status
- Cancel Bookings
- Free & Paid Event Support

---

## Admin Features

- Create Events
- Edit Events
- Delete Events
- Approve/Reject Bookings
- Mark Payments as Paid/Unpaid
- Dashboard Analytics
- Revenue & Pending Request Tracking

---

## Booking System

- OTP-secured Booking Flow
- Pending Verification Queue
- Seat Availability Management
- Overbooking Prevention Logic

---

## Email System

- OTP Emails
- Booking Confirmation Emails
- Notification Emails
- Nodemailer Integration

---

## UI/UX

- React + Tailwind CSS
- Responsive Design
- Modern UI
- Mobile Friendly
- Smooth Micro Interactions

---

# Tech Stack

## Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM

---

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcryptjs
- Nodemailer

---

# Project Structure

```bash
Eventora-MERN/
│
├── client/
│   ├── src/
│   ├── public/
│   └── dist/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── utils/
│   └── server.js
│
├── package.json
└── README.md
```

---

# Installation & Setup

## Clone Repository

```bash
git clone https://github.com/kaveri514/Eventora-MERN.git
```

```bash
cd Eventora-MERN
```

---

# Install Dependencies

```bash
npm install
```

```bash
npm run install:all
```

---

# Environment Variables

Create:

```bash
server/.env
```

Add:

```env
MONGO_URI=your_mongodb_atlas_url

JWT_SECRET=your_secret_key

EMAIL_USER=your_gmail@gmail.com

EMAIL_PASS=your_google_app_password

PORT=5000
```

---

# Run Locally

## Development Mode

```bash
npm run dev
```

---

# Production Build

```bash
npm run build
```

---

# Start Production Server

```bash
npm start
```

---

# Deployment

## Frontend + Backend Hosted On

- Render

## Database Hosted On

- MongoDB Atlas

---

# Deployment Commands

## Build Command

```bash
npm install && npm run install:all && npm run build
```

---

## Start Command

```bash
npm start
```

---

# API Base URL

```bash
https://eventora-mern-ivbf.onrender.com/api
```

---

# Future Improvements

- Razorpay/Stripe Integration
- QR Ticket Generation
- Real-time Notifications
- Advanced Event Filters
- Google Authentication
- Dark Mode

---



GitHub:
https://github.com/kaveri514

---

# License

This project is built for learning and portfolio purposes.
