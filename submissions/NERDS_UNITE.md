# CoC Inheritance 2025

## Campus Connected
**Connecting students, resources, and mentorship**  
By **Nerds Unite**

---

## 📝 Description
Campus Connected is a web platform designed to help students collaborate, share academic resources, and connect with seniors for mentorship and guidance. The platform solves the problem of fragmented academic communication by providing a centralized system for resource sharing and mentorship interaction. It is built using the MERN stack with TypeScript, JWT authentication, and MongoDB Atlas.

---

## 🔗 Links
- GitHub Repository: https://github.com/munishmehra374-ctrl/campus_connected.git
- Hosted Website: Not hosted yet

---

## 🤖 Tech Stack

### 🏗️ System Architecture
Frontend (React + TypeScript) communicates with a REST API backend built using Express.js. The backend handles authentication, role-based access, file uploads using Multer, and database operations through MongoDB Atlas.

### Frontend
- React (Vite)
- TypeScript
- Axios

### Backend
- Node.js
- Express.js
- JWT Authentication
- Multer

### Database
- MongoDB Atlas
- Mongoose

---

## 📈 Progress

### Fully Implemented Features
- JWT-based authentication system with protected routes
- Senior–junior mentorship platform with role-based access control
- Resource upload system integrated with MongoDB Atlas

### Partially Implemented Features / Work in Progress
- Deployment configuration for hosting frontend and backend
- Notification system for mentorship interactions

---

## 🔮 Future Scope
- Integration of notification system
- Expansion to mobile-responsive interface
- User authentication updates with additional security layers

---

## 💸 Applications
- Academic Collaboration Platform — Students can share notes and resources
- Mentorship Platform — Seniors can guide juniors through structured interaction

---

## 🛠 Project Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/munishmehra374-ctrl/campus_connected.git
cd campus_connected

cd backend

npm install

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

npm run dev

cd campus_connected/frontend
npm install
npm run dev
