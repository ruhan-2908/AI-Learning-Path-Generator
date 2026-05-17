# SkillBridge

<img src="./frontend/public/full-logo.png" alt="SkillBridge" width="400" height="400" style="margin: 0 auto; display: block; border-radius: 3px">

## AI-Powered Personalized Learning Path Generator

SkillBridge is an AI-powered personalized learning path generation platform designed to help learners identify the right skill development journey based on their current skills, qualifications, and career aspirations. The system analyzes learner profiles and generates structured learning recommendations aligned with NSQF and NCVET standards.


---

# Key Features

- AI-powered personalized learning path generation
- NSQF and NCVET aligned recommendations
- Secure JWT-based authentication system
- User profile and skill management
- Learning progress tracking
- Vector-based recommendation search using Qdrant

---

# Tech Stack

## Frontend
- React
- Tailwind CSS

## Backend
- Node.js
- Express.js
- MongoDB Atlas
- Nodemailer

## AI Recommendation Engine
- Gemini API
- Groq API
- Tavily API
- Qdrant Vector Database
- Inngest

---

# Prerequisites

Make sure the following are installed before running the project:

- Node.js
- npm
- MongoDB Atlas account
- Python 3.8+
- Git
- VS Code (recommended)

---

# Environment Variables

## Backend `.env`

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email@gmail.com
SMTP_PASS=your_gmail_app_password

OTP_EXPIRE_MIN=10
```

---

## AI Recommendation Engine `.env`

```env
GROQ_API_KEY=your_groq_api_key

QDRANT_URL=your_qdrant_url
QDRANT_API_KEY=your_qdrant_api_key

GOOGLE_API_KEY=your_gemini_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

# Installation Instructions

## Clone the Repository

```bash
git clone https://github.com/nithish-github07/SkillBridge.git
```

---

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

## Frontend Setup

```bash
cd frontend
npm run dev
```

---

## AI Recommendation Engine Setup

```bash
cd recommendation-engine
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

---

# Future Enhancements

- Integration with government skill portals
- Real-time labor market analysis
- AI chatbot mentor support
- Mobile application
- Advanced analytics dashboard
- Multi-language support