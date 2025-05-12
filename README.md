

# Edemy LMS 🎓 - A Modern Learning Management System


Edemy LMS is a full-stack learning management system (LMS) that provides educators and students with a seamless e-learning experience. Built using modern web technologies, it includes user authentication, course management, video streaming, and progress tracking.

## 🚀 Tech Stack

## 🛠️ Tech Stack

### 🖥️ Frontend

- **React (via Vite)** – High-performance frontend framework with fast refresh and build times.
- **React Router DOM** – Enables seamless client-side routing for dynamic navigation between pages.
- **React Toastify** – Provides clean, customizable toast notifications for user feedback.
- **Framer Motion** – Used for implementing fluid animations and transitions to enhance UI/UX.
- **Quill** – Rich text editor integration for advanced text formatting capabilities.
- **Axios** – Simplifies HTTP requests and API communication with the backend.
- **RC Progress** – Visual progress bars and indicators to track task or upload progress.
- **React YouTube** – Embeds and controls YouTube videos within the application.
- **Clerk Authentication** – User authentication and session management system for secure access control.

### 🔧 Backend

- **Node.js & Express.js** – Handles server-side logic, API routes, and middleware with scalability.
- **MongoDB & Mongoose** – NoSQL database with schema modeling for data storage and retrieval.
- **Cloudinary** – Cloud-based media management for storing and delivering images and videos.
- **Multer** – Middleware for handling file uploads, especially multipart/form-data.
- **Stripe** – Integrates payment processing, allowing secure and flexible transaction handling.
- **CORS** – Enables cross-origin resource sharing for frontend-backend communication.
- **Dotenv** – Loads environment variables from a `.env` file to manage sensitive configuration.
- **Nodemon** – Automatically restarts the server during development when code changes are detected.


## 📂 Project Structure

### **Frontend (`client/`)**
```
📦 client
 ├── 📂 src
 │   ├── 📂 assets
 │   ├── 📂 components
 │   │   ├── 📂 educator
 │   │   │   ├── Footer.jsx
 │   │   │   ├── Navbar.jsx
 │   │   │   ├── Sidebar.jsx
 │   │   ├── 📂 student
 │   │   │   ├── Logger.jsx
 │   ├── 📂 context
 │   │   ├── AppContext.jsx
 │   ├── 📂 pages
 │   │   ├── 📂 educator
 │   │   │   ├── AddCourse.jsx
 │   │   │   ├── Dashboard.jsx
 │   │   │   ├── Educator.jsx
 │   │   │   ├── MyCourses.jsx
 │   │   │   ├── StudentsEnrolled.jsx
 │   │   ├── 📂 student
 │   │   │   ├── CourseDetails.jsx
 │   │   │   ├── CoursesList.jsx
 │   │   │   ├── Home.jsx
 │   │   │   ├── MyEnrollMents.jsx
 │   │   │   ├── Player.jsx
 │   │   ├── App.jsx
 │   │   ├── index.css
 │   │   ├── main.jsx
 ├── 📜 .env
 ├── 📜 .gitignore
 ├── 📜 package.json
 ├── 📜 tailwind.config.js
 ├── 📜 vite.config.js

```

### **Backend (`server/`)**
```
📦 server
 ├── 📂 configs
 │   ├── cloudinary.js
 │   ├── mongodb.js
 │   ├── multer.js
 ├── 📂 controllers
 │   ├── courseController.js
 │   ├── educatorController.js
 │   ├── userController.js
 │   ├── webhooks.js
 ├── 📂 middlewares
 │   ├── authMiddleware.js
 ├── 📂 models
 │   ├── Course.js
 │   ├── CourseProgress.js
 │   ├── Purchase.js
 │   ├── User.js
 ├── 📂 routes
 │   ├── courseRoute.js
 │   ├── educatorRoutes.js
 │   ├── userRoutes.js
 ├── 📜 .env
 ├── 📜 .gitignore
 ├── 📜 package.json
 ├── 📜 server.js
 ├── 📜 vercel.json
```

---

## 🌟 Features

✅ **User Authentication** (Signup, Login, Clerk Integration)  
✅ **Course Management** (Add, Edit, Delete, Enroll)  
✅ **Video Streaming** (Embedded YouTube player)  
✅ **Progress Tracking** (Course Completion)  
✅ **Educator Dashboard** (Monitor students)  
✅ **Secure Payments** (Stripe integration)  
✅ **Responsive Design** (Mobile-friendly UI)  

---

## 📸 Screenshots

### 🏠 Home Page
![Home](https://github.com/user-attachments/assets/03cf6bd7-8c30-4817-ad49-4a8fe8000541)

### 📚 Course Page
![Course](https://github.com/user-attachments/assets/e42c2660-8271-42ae-b7e3-c5278b6a9cf1)

### 🎓 My Enrollments
![Enrollments](https://github.com/user-attachments/assets/a88cf7c1-cab1-4106-a64d-d7cfd5d9d4b7)

### ▶️ Player Page
![Player](https://github.com/user-attachments/assets/cdc8fb2a-6f44-416f-b4bd-2f35b7acfbbd)

### ➕ Add Course
![Add Course](https://github.com/user-attachments/assets/ee846dba-7b14-4006-ae95-8ff76402ed8d)

### 📁 My Courses
![My Courses](https://github.com/user-attachments/assets/e9f1b602-fc46-4dd7-8833-f1d8b15f43a1)









## ⚡ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/username/Edemy-LMS.git
cd edemy-lms
```

### 2️⃣ Install Dependencies

#### Frontend:
```bash
cd client
npm install
npm run dev
```

#### Backend:
```bash
cd server
npm install
npm start
```

### 3️⃣ Setup Environment Variables
Create a `.env` file in both `client/` and `server/` directories and add required credentials (MongoDB, Cloudinary, Clerk, Stripe, etc.).

---

## 🔥 Deployment

This project is set up for deployment on **Vercel**.

### Deploy Backend
```bash
cd server
vercel --prod
```

### Deploy Frontend
```bash
cd client
vercel --prod
```

---

## 🔐 License
This project is licensed under the [MIT License](LICENSE).

---
