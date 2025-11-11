# 🎓 LearnPath – Choose Your Learning Path

**Live Demo:** [https://frontend-fullstack-tau.vercel.app/](https://frontend-fullstack-tau.vercel.app/)  
**GitHub Repository:** [https://github.com/Studentcuchd/LearnPath-Choose-Your-Learning-Path](https://github.com/Studentcuchd/LearnPath-Choose-Your-Learning-Path)

---

## 🚀 Overview

**LearnPath** is a full-stack interactive learning platform that allows users to explore different skill paths, track their progress, and learn step-by-step through structured checklists.  
It features an elegant interface, smooth interactivity, and real-time progress updates powered by a **MERN stack** backend.

Built using **MongoDB, Express.js, React.js, and Node.js**, it delivers a seamless experience with clean and responsive **CSS styling**.

---

## 🧩 Key Features

- ✅ **User Authentication** – Secure sign-up and login using JWT.  
- 📚 **Skill Path Selection** – Choose from multiple learning categories like Frontend, Backend, etc.  
- 📊 **Dynamic Progress Tracking** – Updates automatically when checklist items are marked.  
- 💾 **Persistent Data Storage** – MongoDB ensures skill data is retained after refresh.  
- 🖥️ **Interactive Dashboard** – View current learning progress visually.  
- 🧾 **Custom Checklists** – Manage learning items under each category.  
- 📱 **Responsive UI** – Built using **Vanilla CSS** for all screen sizes.  
- ⚙️ **MERN Stack Architecture** – Scalable and maintainable full-stack foundation.

---

## 🛠️ Tech Stack

| Category | Technology Used |
|-----------|-----------------|
| **Frontend** | React.js, CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas |
| **Authentication** | JWT (JSON Web Token) |
| **Deployment** | Vercel (Frontend), Render/Railway (Backend) |
| **Version Control** | Git & GitHub |

---

## 🧭 Folder Structure

```
MY-PROJECT/
├── backend/
│   ├── config/           # Database and environment configurations
│   ├── controllers/      # Logic for handling routes
│   ├── middleware/       # Authentication & error handling middleware
│   ├── models/           # MongoDB models/schemas
│   ├── routes/           # Express routes
│   ├── utils/            # Utility/helper functions
│   ├── .env              # Environment variables
│   ├── package.json      # Backend dependencies
│   ├── package-lock.json
│   └── server.js         # Entry point for backend server
│
├── frontend/
│   ├── public/           # Static files and index.html
│   ├── src/
│   │   ├── components/   # Reusable React components
│   │   ├── data/         # Static or mock data
│   │   ├── hooks/        # Custom React hooks
│   │   ├── pages/        # Main page components (Dashboard, Skills, etc.)
│   │   ├── styles/       # CSS stylesheets
│   │   ├── utils/        # Frontend utility functions
│   │   ├── App.js        # Root React component
│   │   └── index.js      # Entry point for React app
│   ├── .env              # Frontend environment variables
│   ├── package.json      # Frontend dependencies
│   └── package-lock.json
│
└── README.md             # Project documentation
```

---

## ⚙️ Environment Variables

Create `.env` files in both the **backend** and **frontend** directories.

### Backend `.env`
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Frontend `.env`
```env
REACT_APP_API_URL=http://localhost:5000
```

---

## 🧑‍💻 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Studentcuchd/LearnPath-Choose-Your-Learning-Path.git
cd LearnPath-Choose-Your-Learning-Path
```

### 2️⃣ Install Dependencies
#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd ../frontend
npm install
```

### 3️⃣ Run the Application

#### Start Backend
```bash
node server.js
```
Runs the backend server at **http://localhost:5000**

#### Start Frontend
```bash
npm start
```
Runs the frontend app at **http://localhost:3000**

---

## 🌐 Deployment

- **Frontend:** Hosted on [Vercel](https://vercel.com/)  
- **Backend:** Hosted on [Render](https://render.com/) or [Railway](https://railway.app/)  
- **Database:** Managed via [MongoDB Atlas](https://www.mongodb.com/atlas/database)

---

## 🧩 Future Enhancements

- 🧠 Add **quiz system** for each learning path.  
- 🧑‍🏫 Add **mentor/teacher dashboards** for managing users.  
- 📈 Add **analytics and visual progress charts**.  
- 🔔 Implement **email notifications/reminders** for users.  
- 🤖 Introduce **AI-based learning recommendations**.

---

## 👨‍💻 Developer

**Developed by:** [Parag Bajaj](https://github.com/Studentcuchd)  
🎯 *Full Stack Developer | MERN | AI & Cloud Enthusiast*
