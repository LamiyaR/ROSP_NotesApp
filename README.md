# ROSP Notes App

A full-stack notes management application built with **React**, **Node.js**, **Express**, and **MongoDB**.  
It provides a clean interface to create, edit, delete, and organize notes with user authentication and dark mode support.

---

## 🚀 Features
- 🔐 User Authentication (JWT-based)
- 📝 Create, Read, Update, Delete (CRUD) notes
- 🌙 Dark mode toggle
- 📱 Responsive design
- ⚡ RESTful API backend with Express.js
- 💾 MongoDB integration

---

## 🛠️ Tech Stack
- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT & Middleware validation

---

## 📂 Project Structure
\`\`\`
ROSPNotesApp/
├── controllers/      # Business logic for Auth, Notes, Home
├── routes/           # Express routers for API endpoints
├── Middlewares/      # Auth & validation middleware
├── config/           # Database configuration
├── public/           # Static assets
├── src/              # React frontend (components, pages, utils)
└── ...
\`\`\`

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
\`\`\`bash
git clone https://github.com/yLamiyaR/ROSP_NotesApp.git
cd ROSPNotesApp
\`\`\`

### 2️⃣ Install dependencies
\`\`\`bash
# Install backend dependencies
npm install

# Navigate to frontend (if separate) and install
cd src
npm install
\`\`\`

### 3️⃣ Configure environment variables
Create a `.env` file in the root with:
\`\`\`
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
\`\`\`

### 4️⃣ Run the development servers
\`\`\`bash
# Run backend
npm start

# Run frontend (in separate terminal, if needed)
cd src
npm start
\`\`\`

App should now be running at:  
👉 Frontend: http://localhost:3000  
👉 Backend: http://localhost:5000

---

## 📸 Screenshots
*(Add screenshots here if available)*

---

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📜 License
This project is licensed under the MIT License.
