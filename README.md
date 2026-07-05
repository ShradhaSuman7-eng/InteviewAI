# 🎯 AI Interview Platform

A Full Stack AI-powered Interview Preparation Platform built using the MERN Stack.

The application allows users to register/login securely, upload resumes, generate AI-powered interview questions, receive personalized interview reports, identify skill gaps, and follow a customized learning roadmap.

---

## Features

### Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes
- Logout
- Password Hashing using bcrypt

### Resume Processing

- Upload PDF Resume
- Extract Resume Text
- Validate Uploaded Files

### AI Interview

- Resume Analysis
- AI Generated Interview Questions
- Expected Answers
- Interview Intentions
- Skill Gap Detection
- Match Score
- Personalized Roadmap

### Dashboard

- Interview Report
- Questions & Answers
- Match Percentage
- Skill Gap Visualization
- Learning Roadmap

---

# Tech Stack

## Frontend

- React
- React Router
- Axios
- SCSS
- Vite

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Multer
- PDF Parse
- Google Gemini AI

---

# Project Structure

```
interview-ai-yt
│
├── Backend
│   ├── src
│   │   ├── config
│   │   │   └── database.js
│   │   │
│   │   ├── controllers
│   │   │   ├── auth.controller.js
│   │   │   └── interview.controller.js
│   │   │
│   │   ├── middlewares
│   │   │   ├── auth.middleware.js
│   │   │   └── file.middleware.js
│   │   │
│   │   ├── models
│   │   │   ├── user.model.js
│   │   │   ├── interviewReport.model.js
│   │   │   └── blacklist.model.js
│   │   │
│   │   ├── routes
│   │   │   ├── auth.routes.js
│   │   │   └── interview.routes.js
│   │   │
│   │   ├── services
│   │   │   └── ai.service.js
│   │   │
│   │   └── app.js
│   │
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── Frontend
│   ├── src
│   │
│   │── features
│   │
│   │   ├── auth
│   │   │   ├── components
│   │   │   │   └── Protected.jsx
│   │   │   │
│   │   │   ├── hooks
│   │   │   │   └── useAuth.js
│   │   │   │
│   │   │   ├── pages
│   │   │   │   ├── Login.jsx
│   │   │   │   └── Register.jsx
│   │   │   │
│   │   │   ├── services
│   │   │   ├── auth.context.jsx
│   │   │   └── auth.form.scss
│   │   │
│   │   ├── interview
│   │   │   ├── hooks
│   │   │   │   └── useInterview.js
│   │   │   │
│   │   │   ├── pages
│   │   │   │   ├── Home.jsx
│   │   │   │   └── Interview.jsx
│   │   │   │
│   │   │   ├── services
│   │   │   │   └── interview.api.js
│   │   │   │
│   │   │   ├── style
│   │   │   │   ├── home.scss
│   │   │   │   └── interview.scss
│   │   │   │
│   │   │   └── interview.context.jsx
│   │
│   │── style
│   │   └── style.scss
│   │
│   │── App.jsx
│   │── app.routes.jsx
│   │── main.jsx
│   │
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone <repository-url>
```

---

## Backend

```bash
cd Backend
```

Install dependencies

```bash
npm install
```

Create `.env`

```env
PORT=3000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

GOOGLE_API_KEY=your_google_api_key
```

Run server

```bash
npm run dev
```

---

## Frontend

```bash
cd Frontend
```

Install dependencies

```bash
npm install
```

Run

```bash
npm run dev
```

---

# Environment Variables

Backend `.env`

```env
PORT=

MONGO_URI=

JWT_SECRET=

GOOGLE_API_KEY=
```

---

# Backend Packages

- Express
- Mongoose
- JWT
- bcryptjs
- Multer
- dotenv
- cors
- cookie-parser
- pdf-parse
- Google GenAI
- Puppeteer
- Zod

---

# Future Improvements

- Mock Interview Session
- Voice Interview
- AI Feedback
- Coding Interview Support
- Dashboard Analytics
- Interview History
- Multiple Resume Support
- Dark/Light Theme

---

GitHub:https://github.com/ShradhaSuman7-eng/InteviewAI
