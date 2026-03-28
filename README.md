
# 📄 Receipt & Invoice Digitizer

A modern **full-stack web application** designed to simplify the process of managing, extracting, and analyzing receipts and invoices digitally.

Built with a powerful combination of **React (frontend)** and **FastAPI (backend)** for speed, scalability, and a smooth user experience.

---

## ✨ Key Highlights

* 📂 **Smart Document Storage**
  Upload and organize receipts & invoices in one place

* 🔐 **Secure Authentication**
  Google OAuth-based login system

* 🤖 **Automated Data Extraction**
  Extract key information from uploaded files

* 📊 **Interactive Dashboard**
  Visualize expenses using charts and analytics

* 📄 **PDF Export**
  Generate clean and professional reports

* 📱 **Responsive UI**
  Works seamlessly across devices

---

## 🧰 Tech Overview

### 🎨 Frontend

* React (Vite)
* Tailwind CSS
* React Router DOM
* Axios
* Recharts
* Framer Motion
* Google OAuth
* jsPDF & html2canvas

### ⚙️ Backend

* FastAPI
* Uvicorn
* SQLAlchemy
* Pydantic
* JWT (Python-Jose)
* Passlib (Bcrypt)
* SQLite
* Python-dotenv

---

## 📁 Folder Structure

```
project-root/
│
├── frontend/        # React application
│
├── backend/         # FastAPI server
│   ├── app/
│   │   ├── api/
│   │   ├── core/
│   │   ├── db/
│   │   ├── models/
│   │   ├── services/
│   │   └── main.py
│
└── README.md
```

---

## 🚀 Getting Started

### 🔧 Requirements

* Node.js (v16+)
* Python (v3.8+)
* npm / yarn
* pip

---

## ⚙️ Backend Setup

```bash
cd backend
python -m venv venv
```

### Activate environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Create `.env`

```
DATABASE_URL=sqlite:///app.db
SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
```

### Run server

```bash
uvicorn app.main:app --reload
```

👉 Backend runs at: `http://localhost:8000`

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
```

### Environment file

```
VITE_API_URL=http://localhost:8000
VITE_GOOGLE_CLIENT_ID=your_client_id
```

### Start app

```bash
npm run dev
```

👉 Frontend runs at: `http://localhost:5173`

---

## 🔗 API Access

Explore backend APIs via:

* Swagger UI → `/docs`
* ReDoc → `/redoc`

---

## 🔐 Authentication Flow

* Google OAuth for user login
* JWT tokens for API security
* Password hashing using Bcrypt

---

## 📦 Environment Variables

### Backend

```
DATABASE_URL=
SECRET_KEY=
ALGORITHM=
ACCESS_TOKEN_EXPIRE_MINUTES=
```

### Frontend

```
VITE_API_URL=
VITE_GOOGLE_CLIENT_ID=
```

---

## 🛠️ Development Tips

* Use `--reload` in backend for auto restart
* Use `npm run dev` for frontend hot reload
* Database auto-creates on first run

---

## 📜 Scripts

### Frontend

* `npm run dev`
* `npm run build`
* `npm run preview`

### Backend

* `uvicorn app.main:app --reload`

---

## 🤝 Contribution Guide

1. Fork the repository
2. Create a new branch
3. Make changes
4. Submit a pull request

---

## 📄 License

Refer to the LICENSE file for details.

---

## 👨‍💻 Author

Developed by **Rethika S**




