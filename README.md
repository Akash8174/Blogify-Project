# 📝 Blogify - Blogging Platform

A **server-side blogging application** built using **Node.js, Express.js, MongoDB, and EJS**.  
This project allows users to create, manage, and read blog posts with authentication and file upload support.

---

## 🚀 Features
- ✍️ **Create, Edit & Delete Blog Posts**
- 🔐 **User Authentication** with JWT
- 🖼️ **Image Uploads** using Multer
- 📖 **Read Blogs** with EJS templates
- 🍪 **Cookie-based Authentication** with cookie-parser
- 🌍 **Environment Variables** managed with dotenv
- 🗄️ **MongoDB & Mongoose** for database

---

## 🛠️ Tech Stack
**Core**
- Node.js  
- Express.js  
- MongoDB (Mongoose ODM)  

**Templating**
- EJS  

**Authentication**
- JSON Web Tokens (JWT)  
- cookie-parser  

**File Upload**
- Multer  

**Development**
- Nodemon  

---

## ⚡ Getting Started
### 1️⃣ Clone the repository
  ```bash
  git clone https://github.com/Akash8174/Blogify-Project.git
  cd Blogify-Project
2️⃣ Install dependencies
  ```bash
  npm install
3️⃣ Setup environment variables
Create .env file in the root:
  ```bash
  MONGO_URI=your_mongodb_connection
  JWT_SECRET=your_secret_key
  PORT=8000
4️⃣ Run the application
  ```bash
  npm run dev
 
