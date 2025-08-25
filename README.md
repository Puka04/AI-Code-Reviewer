# AI-Code-Reviewer

A full-stack application that allows developers to get automated code reviews using AI. The app analyzes submitted code, provides detailed feedback, suggests improvements, and highlights best practices.

## Live Demo
[Check it out here](https://ai-code-reviewer-git-main-pujas-projects-f691864a.vercel.app/)

## Features
- **AI-Powered Code Review:** Uses Google Gemini AI to review code.
- **Frontend:** React + Vite for a fast and interactive UI.
- **Backend:** Node.js + Express server handling AI requests.
- **Cross-Origin Support:** CORS enabled for frontend-backend communication.
- **Deployment:** Fully deployed with Render (backend) and Vercel (frontend).

## Tech Stack
- **Frontend:** React, Vite, Axios
- **Backend:** Node.js, Express
- **AI Service:** Google Gemini AI (`@google/genai` npm package)
- **Hosting:** Render (Backend), Vercel (Frontend)

## Installation (Local)
### Backend
1. Navigate to the backend folder:
   ```bash
   cd backend

2. Install dependencies:
   ```bash
   npm install

3. Create a .env file with your API Key:
   ```env
   GOOGLE_GEMINI_KEY=your_api_key_here

4. Start the server:
   ```bash
   npm start

### Frontend
1. Navigate to the frontend folder:
   ```bash
   cd frontend

2. Install dependencies:
   ```bash
   npm install

3. Update the API URL in your frontend code to point to your backend:
   ```js
   const API_BASE_URL = "http://localhost:5000/ai"; // your deployed backend URL

4. Start the development server:
   ```bash
   npm run dev

##Usage
1. Use the live demo link to test features or run the frontend locally.
2. Enter your code snippet in the input area and click **“Get Review”**.  
3. The AI provides suggestions for readability, maintainability, performance, security, and best       practices.
4. Apply the recommended changes to improve your code.

##Folder Structure

```bash
project-root/
│
├─ backend/          # Node.js + Express backend
│  ├─ src/
│  ├─ package.json
│  └─ .env
│
├─ frontend/         # React + Vite frontend
│  ├─ src/
│  ├─ package.json
│  └─ vite.config.js
│
└─ README.md
