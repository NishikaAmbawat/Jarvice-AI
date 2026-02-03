# Jarvice-AI

# Jarvice AI 🤖

Jarvice AI is a full-stack AI-powered web application that delivers intelligent chat, image generation, and voice-based interview experiences. It integrates a modern React frontend with a secure Node.js backend, authentication, subscriptions, and database-driven workflows.

---

## 🚀 Features

- User authentication with JWT  
- AI-powered chat system  
- AI image generation  
- Voice-based interview module  
- Resume upload and management  
- Interview history tracking  
- Subscription and access control  
- Email notifications  
- Secure REST APIs  

---

## 🧠 Tech Stack

**Frontend:** React.js, Tailwind CSS, Axios  
**Backend:** Node.js, Express.js, JWT  
**Database:** SQL (Relational, migrations included)  
**Tools:** Multer, REST APIs, Environment-based config  

---

## 📁 Project Structure

Jarvice-Ai/
├── client/ # React frontend
│ ├── src/
│ └── public/
├── server/ # Node.js backend
│ ├── routes/
│ ├── middleware/
│ ├── config/
│ ├── utils/
│ ├── migrations/
│ ├── uploads/
│ └── init-db.sql
└── README.md


**Client (.env)**
REACT_APP_API_BASE_URL=http://localhost:5000


Backend:
cd server
npm install
npm start


Frontend:
cd client
npm install
npm start

📌 API Modules

/auth – Authentication & authorization

/user – User profile management

/chat – AI chat processing

/image – AI image generation

/interview – AI & voice interviews

/subscription – Subscription handling

🔒 Security
Password hashing
JWT-based protected routes
Middleware-driven access control
Secure environment variables

👤 Author

Nishika Ambawat
Computer Science Engineering | Full-Stack Developer
Focused on scalable backend systems and AI-driven products.
