# Code Review – MERN Stack Project

This project is a **MERN Stack** application designed for code reviewing and related functionalities.  
It includes a **Node.js + Express** backend and (optionally) a frontend built with React.

---

## 📂 Project Structure
```
code-review/
 ├── BackEnd/          # Backend server code
 │    ├── server.js    # Entry point for Node.js server
 │    ├── package.json # Backend dependencies
 │    ├── .env         # Environment variables
 └── FrontEnd/         # (If present) React app for the frontend
```

---

## ⚙️ Requirements

Before running this project, make sure you have installed:

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [MongoDB](https://www.mongodb.com/try/download/community) (if the backend uses a database)
- [Git](https://git-scm.com/) (for version control)

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd code-review
```

### 2️⃣ Setup Backend
```bash
cd BackEnd
npm install
```

Create a `.env` file in the `BackEnd` folder with the following variables:
```env
PORT=your port number
GOOGLE_GEMINI_KEY="Your GOOGLE_GEMINI_KEY"

```

### 3️⃣ (Optional) Setup Frontend
If you have a frontend folder:
```bash
cd ../FrontEnd
npm install
```
Create a `.env` file for frontend if needed (example):
```env
VITE_API_URL=http://localhost:5000
```

---

## ▶️ Running the Application

### Start Backend
```bash
cd BackEnd
npm start
```
This will start the server on the port specified in `.env` (default: **5000**).

### Start Frontend (if present)
```bash
cd FrontEnd
npm run dev
```
This will start the React app (default: **http://localhost:5173**).

---

## 📌 Explanation of Setup

1. **Clone repo** → Gets a copy of the code on your machine.
2. **Install dependencies** → Installs all npm packages listed in `package.json`.
3. **Setup `.env`** → Stores configuration values like database connection, API keys, and secrets.
4. **Run backend** → Starts Node.js + Express API server.
5. **Run frontend** → Starts the React development server.

---


