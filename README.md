<div align="center">

  <h1>🎓 Alumni Connect Platform</h1>
  
  <p>
    <strong>Bridge the gap between past and present. Connect, Mentor, Grow.</strong>
  </p>

</div>


## 🚀 Overview

**Alumni Connect** is a comprehensive platform designed to foster a vibrant community between alumni, students, and faculty. It facilitates networking, mentorship, job opportunities, and event management in a seamless, modern digital environment. Built with the MERN stack and Supercharged with real-time capabilities.

---
<img width="1895" height="904" alt="image" src="https://github.com/user-attachments/assets/55d12850-02d0-4e5c-a835-7cbcfe28b699" />

---

## ✨ Key Features

| 🌟 Feature | 📝 Description |
|:---|:---|
| **👥 Alumni Directory** | Search and connect with alumni based on batch, branch, and company. |
| **💼 Job Portal** | Alumni can post job openings; students can browse and apply directly. |
| **📅 Events & Gallery** | Manage reunions, webinars, and view photo galleries from past events. |
| **💬 Real-time Chat** | Instant messaging between users powered by **Socket.IO**. |
| **🤝 Mentorship** | Dedicated program for alumni to mentor students in their career paths. |
| **📢 Campaigns** | Fundraising and awareness campaigns for university initiatives. |
| **📝 Blog System** | Share success stories, industry insights, and university news. |
| **🛡️ Admin Panel** | Robust dashboard for faculty/admins to manage users and content. |
| **🔔 Notifications** | Real-time alerts for messages, event updates, and job postings. |

---

## 🛠️ Dynamic Tech Stack

<div align="center" style="overflow: hidden;">
<marquee behavior="scroll" direction="left" scrollamount="10">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" hspace="10" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" hspace="10" />
  <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Javascript" hspace="10" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind" hspace="10" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" hspace="10" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="SocketIO" hspace="10" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS" hspace="10" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="ExpressJS" hspace="10" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" hspace="10" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT" hspace="10" />
  <img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" alt="Cloudinary" hspace="10" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" hspace="10" />
  <img src="https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git" hspace="10" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux" hspace="10" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" hspace="10" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" hspace="10" />
</marquee>
</div>

---

## 📂 Project Structure

A high-level overview of the application's architecture to help you navigate the codebase.

```bash
Alumni-Platform/
├── 📂 backend/                  # Server-side logic
│   ├── 📂 config/               # DB & Cloudinary configs
│   ├── 📂 controller/           # Route logic (Auth, User, Event, etc.)
│   ├── 📂 middlewares/          # Auth, Validation, Error Handling
│   ├── 📂 models/               # Mongoose Schemas (User, Job, Event)
│   ├── 📂 routes/               # API Endpoints
│   ├── 📂 services/             # Email & Utility services
│   ├── 📂 socket/               # Real-time connection handlers
│   └── 📄 index.js              # Entry point
│
├── 📂 frontend/                 # Client-side application
│   ├── 📂 public/               # Static assets
│   ├── 📂 src/
│   │   ├── 📂 components/       # Reusable UI components (Header, Footer, Cards)
│   │   ├── 📂 context/          # Context API (Theme, Auth, Socket)
│   │   ├── 📂 pages/            # Page components
│   │   │   ├── 📂 admin/        # Admin Dashboard & Management
│   │   │   ├── 📄 Home.jsx      # Landing Page
│   │   │   ├── 📄 Dashboard.jsx # User Dashboard
│   │   │   └── ...              # 30+ other specialized pages
│   │   ├── 📄 App.jsx           # Main Router
│   │   └── 📄 main.jsx          # React Entry
│   └── 📄 vite.config.js        # Build configuration
│
└── 📄 README.md                 # Project Documentation
```

---

## 📸 Gallery

<div align="center">
  <div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/c797b9ff-d85f-4aff-9ea2-6b106159d2f3" alt="Dashboard" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Alumni+Directory" alt="Directory" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
  </div>
  <div style="display: flex; justify-content: space-between;">
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Job+Portal" alt="Jobs" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Chat+Interface" alt="Chat" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
  </div>
   <div style="display: flex; justify-content: space-between;">
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Job+Portal" alt="Jobs" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Chat+Interface" alt="Chat" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
  </div>
   <div style="display: flex; justify-content: space-between;">
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Job+Portal" alt="Jobs" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
    <img src="https://placehold.co/600x400/1e293b/FFF?text=Chat+Interface" alt="Chat" width="48%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
  </div>
</div>

---

## 💡 Have an Idea?

This project is currently maintained internally. However, innovation works best when shared! If you have a feature request, a new idea, or want to integrate something new:

**Please contact the admin directly.**

> *We represent the bridge between innovation and execution.*

---

## 📞 Contact

**Project Admin** - **Harsh Manmode**
*   📧 Email: [harshmanmode79@gmail.com](mailto:harshmanmode79@gmail.com)
*   🌐 Website: [https://alumni.mitsgwalior.in/](https://alumni.mitsgwalior.in/)

<div align="center">
  <br />
  <p>Made with ❤️ by <strong>Harsh Manmode (IT)</strong></p>
  <p>© 2026 Alumni Connect Platform. All Rights Reserved.</p>
</div>
