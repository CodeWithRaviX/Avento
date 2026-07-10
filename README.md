# 🎉 Avento – Full-Stack MERN Event Booking Platform

 Avento is a modern **full-stack MERN Event Booking Platform** that enables users to discover events, book tickets securely with OTP verification, and allows administrators to manage events, bookings, and payments through a powerful dashboard.

Built using the **MERN Stack**, JWT Authentication, MongoDB Atlas, Nodemailer, and Tailwind CSS.

---

## 🚀 Features

### 👤 User Features

- Secure JWT Authentication
- Email OTP verification during registration
- OTP verification before booking confirmation
- Browse free and paid events
- Book event tickets
- View booking history and booking status
- Cancel pending bookings
- Responsive modern UI

### 🔐 Admin Features

- Secure Admin Dashboard
- Create, edit and delete events
- Manage free and paid events
- Approve or reject booking requests
- Mark bookings as Paid / Unpaid
- View analytics dashboard
- Manage seat availability
- Prevent overbooking

### 📧 Email Services

- Registration OTP
- Booking OTP
- Booking confirmation emails

---

# 🛠 Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Router
- Axios

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- bcrypt.js
- Nodemailer

---

# 📂 Project Structure

```
Eventora/
│
├── client/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── utils/
│   ├── .env
│   └── package.json
│
└── README.md
```

---

# ⚙️ Environment Variables

Create a `.env` file inside the **server** folder.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_gmail_app_password

PORT=5000
```

Example MongoDB URI

```env
MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/eventora?retryWrites=true&w=majority
```

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Eventora.git
```

Move into the project

```bash
cd Eventora
```

---

## Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd ../client
npm install
```

---

# ▶️ Run the Project

### Start Backend

```bash
cd server
npm run dev
```

Runs on

```
http://localhost:5000
```

### Start Frontend

```bash
cd client
npm run dev
```

Runs on

```
http://localhost:5173
```

---

# ✨ Key Functionalities

- JWT Authentication
- Email OTP Verification
- Role-based Authorization
- Event Management
- Booking Management
- Admin Analytics Dashboard
- Seat Capacity Validation
- Overbooking Prevention
- Responsive Design
- MongoDB Atlas Integration

---

# 📸 Screenshots

> Add screenshots here

- Home Page
- Event Details
- Login
- Register
- User Dashboard
- Admin Dashboard
- Booking Page

---

# 🔮 Future Improvements

- Razorpay / Stripe Payment Gateway
- QR Code Ticket Generation
- Google Login
- Event Search & Filters
- User Profile Management
- Event Reviews & Ratings
- Real-time Notifications

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developer

**Ravi Kishan Yadav**

- GitHub: https://github.com/CodeWithRaviX

⭐ If you found this project helpful, don't forget to star the repository!