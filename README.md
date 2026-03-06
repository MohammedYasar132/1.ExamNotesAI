# AeroNotes AI – AI Powered Exam Notes Generation Platform

AeroNotes AI is a **SaaS-style AI learning platform** that automatically generates structured exam notes, diagrams, charts, and revision summaries using Large Language Models (LLMs).

The platform helps students quickly generate **high-quality study material for any topic** including:

* Concept explanations
* Revision points
* Diagrams
* Charts
* Practice questions
* Downloadable PDF notes

This project demonstrates **AI-powered content generation, prompt engineering, data visualization, and SaaS architecture** in a full-stack application.

---

# 🚀 Features

### 📚 AI Generated Exam Notes

Users enter a topic and the system generates:

* Structured explanations
* Key concepts
* Exam-focused summaries
* Important revision points

The AI ensures the notes are **clear, concise, and exam-ready**.

---

### 🧠 LLM Powered Content Generation

The system uses **Large Language Models (LLMs)** to generate educational content.

AI generates:

* Topic breakdown
* Subtopics
* Study notes
* Exam-style questions

Prompt engineering ensures **consistent and structured outputs**.

---

### 📊 AI Generated Charts

AI converts relevant data into visual charts using **Recharts** to improve understanding of complex topics.

Examples:

* Comparison charts
* Process flows
* Concept relationships

---

### 📈 AI Generated Diagrams

The platform generates **Mermaid diagrams** for visual learning.

Examples include:

* Flowcharts
* Concept diagrams
* Process visualization

---

### 📝 Markdown Based Content Rendering

AI generated notes are rendered using **Markdown** for clean formatting including:

* Headings
* Bullet points
* Code blocks
* Tables
* Structured explanations

---

### 📄 PDF Export

Users can **download generated notes as a PDF** for offline study.

PDF generation ensures:

* Clean formatting
* Printable layout
* Structured note presentation

---

### 💳 Credit Based SaaS Model

The platform uses a **credit-based usage system**.

Each AI generation consumes credits.
Users can purchase additional credits to generate more notes.

---

### 💰 Payment Integration

Secure payment system integrated for purchasing credits.

The system verifies payments and updates user credits automatically.

---

### 🔐 Authentication

Secure authentication system using:

* Google Authentication
* JWT session handling
* Cookie-based login

---

# 🏗️ Tech Stack

## Frontend

* React.js
* Framer Motion
* Markdown Rendering
* Recharts (Data Visualization)
* Mermaid.js (Diagram Generation)
* Axios

## Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication

## AI Integration

* Google Gemini API (LLM)

## Payment System

* Stripe / Razorpay

## Deployment

* Render

---

# ⚙️ System Architecture

User enters topic
↓
Frontend sends request to backend
↓
Prompt engineering generates structured prompt
↓
LLM API generates exam notes
↓
Backend parses AI response
↓
Frontend renders notes, charts, and diagrams
↓
User can export notes as PDF

---

# 📂 Project Structure

ExamNotesAI
│
├── client
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── hooks
│   │   ├── utils
│   │   └── services
│
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── services
│   └── utils

---

# 🧑‍💻 Installation

## Clone the Repository

git clone https://github.com/your-username/examnotes-ai.git
cd examnotes-ai

---

## Install Dependencies

### Frontend

cd client
npm install

### Backend

cd server
npm install

---

## Start the Application

### Start Backend

cd server
npm run dev

### Start Frontend

cd client
npm run dev

---

# 🔐 Environment Variables

Create a `.env` file inside the **server folder**.

Example configuration:

PORT=8000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
STRIPE_SECRET_KEY=your_stripe_key

---

# 🌐 Deployment

The project can be deployed using **Render**.

Deployment steps:

1. Push repository to GitHub
2. Connect GitHub repository to Render
3. Configure environment variables
4. Deploy backend service
5. Deploy frontend service
6. Connect MongoDB Atlas database

---

# 📈 Future Improvements

* AI generated flashcards
* Personalized learning recommendations
* Quiz generation from notes
* Study progress tracking
* Multi-language notes generation
* AI tutor chat system

---

# 👨‍💻 Author

Mohammed Yasar
MERN Stack Developer | AI Applications Builder

GitHub: https://github.com/MohammedYasar132

---

# ⭐ Support

If you like this project, please give it a ⭐ on GitHub.
It helps others discover the project.
