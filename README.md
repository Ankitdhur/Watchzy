# 🎬 Watchzy – Full Stack Movie Streaming Platform

Watchzy is a full-stack movie streaming platform built with **Next.js** (frontend) and **Node.js + Express + MongoDB** (backend).  
It features authentication, payments via Razorpay, TMDB API integration, and email services.

---

## ✨ Features
- 🎬 Movie browsing with TMDB API integration  
- 🔐 JWT-based authentication  
- 💳 Razorpay payment gateway integration  
- 📧 Email notifications via Gmail SMTP  
- 🎨 Responsive, modern UI with Next.js  
- 📦 Full-stack architecture with separate frontend and backend  

---

## 🛠 Tech Stack
**Frontend**
- Next.js  
- React.js  
- Tailwind CSS  

**Backend**
- Node.js  
- Express.js  
- MongoDB & Mongoose  
- JWT Authentication  
- Razorpay Integration  
- Nodemailer  

---

## ⚙️ Project Setup

### 1️⃣ Clone Repositories
# Clone frontend
git clone https://github.com/Ankitdhur/Watchzy-Frontend.git
cd watchzy-frontend

# Clone backend (in a separate folder)
git clone https://github.com/Ankitdhur/Watchzy-Backend.git
cd watchzy-backend

### 2️⃣ Backend Setup
Install Dependencies
cd watchzy-backend
npm install

Create .env File
Create a .env file in the backend root directory and add:
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password
DB_NAME=your_db_name
PORT=5000
JWT_SECRET_KEY=your_secret_key
KEY_ID=your_razorpay_key_id
KEY_SECRET=your_razorpay_key_secret
GMAIL_USER=your_gmail_address
GMAIL_APP_PASSWORD=your_gmail_app_password
TMDB_KEY=your_tmdb_api_key

### Start Backend Server
node api.js

### 3️⃣ Frontend Setup
Install Dependencies
cd watchzy-frontend
npm install

Create .env.local File
Create a .env.local in frontend root with:
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000
NEXT_PUBLIC_KEY_ID=your_razorpay_public_key

### ▶ Start Frontend Server
npm run dev




