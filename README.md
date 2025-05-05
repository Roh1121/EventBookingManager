

```
🎉 EventManager_BITS (MERN Stack)

A full-stack Event Management System built using the **MERN** stack. The backend supports user authentication with **JWT**, while the frontend is powered by **React + Vite**. This project is a work-in-progress, with foundational features in place and more to come.

---

🧰 Tech Stack

- **Frontend**: Vite + React
- **Backend**: Node.js + Express
- **Database**: MongoDB + Mongoose
- **Authentication**: JWT (Access Token only)
- **Other Tools**: Axios, CORS, dotenv, bcrypt, nodemon

---
🚀 Features Implemented

✅ Backend
- User registration and login
- JWT-based authentication using access tokens
- CORS support
- MongoDB connection using Mongoose
- Structured API routes

✅ Frontend (Initial Setup)
- Basic UI with a **sidebar** (Genres, Hot Events)
- **Navbar** component added
- Routes configured
- API call setup in progress

---

🛠️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/ThrigunChandra/EventManager_BITS.git
cd EventManager_BITS
```

---

2. Backend Setup

```bash
cd backend
npm install
# Add your .env file with MongoDB URI and JWT secret
npm run dev
```

---

3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

🔒 Environment Variables

Create a `.env` file in the `backend` directory:

```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

---

📌 Upcoming Features

- [ ] Connect frontend with backend via API calls  
- [ ] Sidebar filtering by genres and hot events  
- [ ] Add, view, edit, delete events  
- [ ] User dashboard and profile features  
- [ ] Responsive design using Tailwind CSS  

---

👨‍💻 Author
**Rohini** - [@github](https://github.com/Roh1121)
**ThrigunChandra** – [@github](https://github.com/ThrigunChandra)

---

## 📄 License

This project is licensed under the ISC License.
```
