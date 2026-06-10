# 📚 BookLeaf - Author Support Portal

![MERN](https://img.shields.io/badge/Stack-MERN-green)
![React](https://img.shields.io/badge/Frontend-React-blue)
![Node](https://img.shields.io/badge/Backend-Node.js-brightgreen)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-success)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)

BookLeaf is a full-stack MERN application designed to simplify book management and author support workflows. The platform allows authors to manage their published books, raise support tickets, and track ticket status through an intuitive dashboard while providing administrative functionality for managing support requests.

---

# 🚀 Features

## 🔐 Authentication

- User Registration
- Secure Login
- JWT Authentication
- Password Encryption
- Protected Routes

---

## 📖 Book Management

Authors can:

- Add new books
- View their books
- Manage book information
- Store book details securely

---

## 🎫 Support Ticket System

Users can:

- Raise support tickets
- Track ticket status
- View ticket history
- Communicate support requirements

---

## 👨‍💼 Admin Features

Administrators can:

- View all support tickets
- Update ticket status
- Monitor platform activity
- Manage support workflows

---

# 🏗 Project Architecture

```
BookLeaf
│
├── Frontend (React + Vite)
│   ├── Authentication
│   ├── Dashboard
│   ├── Book Management
│   └── Ticket Management
│
├── Backend (Node + Express)
│   ├── Controllers
│   ├── Routes
│   ├── Middleware
│   └── Models
│
└── MongoDB Atlas
```

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- Bootstrap
- Axios
- React Router DOM
- Tailwind CSS

## Backend

- Node.js
- Express.js
- JWT
- Mongoose
- bcrypt.js
- Multer

## Database

- MongoDB Atlas

## Deployment

- Vercel
- MongoDB Atlas Cloud

---

# 📂 Folder Structure

```
BookLeaf-main/

├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.jsx
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── README.md
└── WRITEUP.md
```

---

# 🔥 Core Functionalities

## Author

✅ Register

✅ Login

✅ Create Books

✅ View Books

✅ Raise Tickets

✅ Track Ticket Status

---

## Admin

✅ View All Tickets

✅ Update Ticket Status

✅ Manage Support Workflow

---

# 🔗 REST API

## Authentication

```
POST /api/auth/register
POST /api/auth/login
```

---

## Books

```
GET /api/books
POST /api/books
```

---

## Tickets

```
POST /api/tickets
GET /api/tickets/my
GET /api/tickets/all
PUT /api/tickets/:id
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/BookLeaf.git

cd BookLeaf-main
```

---

## Backend Setup

```bash
cd backend

npm install

npm run dev
```

---

## Frontend Setup

Open another terminal:

```bash
cd frontend

npm install

npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend directory.

```
PORT=5000

MONGO_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY

OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

---

# 💾 Database Collections

The project uses MongoDB Atlas.

Collections include:

## Users

- Name
- Email
- Password
- Role

## Books

- Title
- Author
- Description
- Owner

## Tickets

- Subject
- Description
- Status
- User

---

# 🔒 Security

- JWT Authentication
- Password Hashing
- Protected APIs
- Authorization Middleware
- Secure User Sessions

---

# 🌐 Deployment

## Frontend

Vercel

## Backend

Vercel

## Database

MongoDB Atlas

---

# 📈 Future Enhancements

- File Upload Support
- Book Cover Images
- Advanced Search
- Ticket Notifications
- Email Verification
- Password Reset
- Real-time Updates
- Analytics Dashboard
- Role-based Access Expansion
- Docker Support
- CI/CD Pipeline

---

# 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- MERN Stack Development
- REST API Design
- JWT Authentication
- MongoDB Integration
- MVC Architecture
- Protected Routes
- CRUD Operations
- Full Stack Deployment
- Modular Backend Development

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# 📄 License

This project is developed for educational and portfolio purposes.

---

# 👨‍💻 Author

## Rishabh Sharma

Full Stack Developer

If you found this project helpful, please consider giving it a ⭐ on GitHub.
