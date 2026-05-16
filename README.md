<div align="center">

  <h1>🎓 Alumni Connect Platform</h1>
  
  <p>
    <strong>Bridge the gap between past and present. Connect, Mentor, Grow.</strong>
  </p>

</div>


## 🚀 Overview
<div  style="max-width: 900px; margin: 20px auto; line-height: 1.6; font-size: 1.1rem; color: #333;">
  <p>
    <strong>Alumni Connect</strong> is a platform that brings together alumni, students, and faculty. 
    It helps with <strong>networking</strong>, <strong>finding mentors</strong>, <strong>job opportunities</strong>, 
    and <strong>managing events</strong>. Built with the <strong>MERN stack</strong>, it also supports 
    <strong>real-time updates</strong> for smooth communication.
  </p>
</div>

---
<img width="1895" height="904" alt="Screenshot 2026-02-18 013308" src="https://github.com/user-attachments/assets/4c0a0775-b85b-47fd-b825-517a9ae81b7c" />



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

## 📸 Gallery

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/c797b9ff-d85f-4aff-9ea2-6b106159d2f3" width="100%" />
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/0d54bb36-b202-4599-92fa-633f10873345" width="100%" />
    </td>
  </tr>

  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/e53cb222-1ab9-4fdf-a790-0ad72b64d42e" width="100%" />
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/814044a5-5e83-46b2-afac-fa98fe65ca73" width="100%" />
    </td>
  </tr>

  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/7f1995e3-3c96-4f67-80c1-92ebd7a191eb" width="100%" />
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/5488da65-7d4b-4efb-a6b1-7ad738124e71" width="100%" />
    </td>
  </tr>
</table>

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
