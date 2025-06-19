# 🏫 Hostel Life Management Platform

A full-stack, open-source platform to empower hostel students with real-time polling, issue reporting, and verified reviews. Designed to give students a voice and help future students and parents make informed choices between hostel and day scholar options.

---

## ✨ Features

- 🗳️ **Mess Food Polling** – Daily votes on food quality with visual charts (Pie, Bar)
- 🛠️ **Issue Reporting System** – Log complaints (Wi-Fi, water heater, power cuts, etc.)
- 🌟 **Play Store-style Review Section** – Hostel reviews and ratings by verified students
- 🧾 **College-wide Hostel Rating System** – Rankings based on alumni and student input
- 🔒 **Verified Participation Only** – OTP/email-based student verification to prevent fake inputs

---

## 🛠️ Tech Stack

### 🚀 Frontend
- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Recharts](https://recharts.org/) (for poll result visualizations)
- Axios

### ⚙️ Backend
- [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) + Mongoose
- [JWT](https://jwt.io/) for authentication
- [Nodemailer](https://nodemailer.com/) for email verification

### ☁️ Deployment (All Free)
- [Vercel](https://vercel.com/) for frontend
- [Render](https://render.com/) for backend
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud database

---

## 📁 Folder Structure
hostel-life-management/
├── client/ # React Frontend
│ └── src/
│ └── components/
│ └── pages/
│ └── utils/
├── server/ # Node.js Backend
│ └── routes/
│ └── models/
│ └── controllers/
│ └── middleware/
├── shared/ # Constants, mock data, etc.
├── .env # Environment variables
├── README.md

✅ Todo
 Admin dashboard for issue tracking

 Role-based access (Admin, Student, Alumni)

 Public dashboard for parents & freshers

 Image upload support in complaints

🧑‍💻 Built By
Two passionate developers solving real-life student problems with code.
Made with ❤️ for students, by students.
