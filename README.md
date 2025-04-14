<div align="center">
  <br />
  <img src="https://raw.githubusercontent.com/adrianhajdin/ai_mock_interviews/refs/heads/main/public/robot.png" alt="Project Banner" width="400" />
  <br /><br />

  <div>
     <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="next.js" />
    <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="vapi" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="firebase" />
  </div>

  <h1 align="center">🎧 Prepwise</h1>
  <h3 align="center">Your AI-Powered Interview Coach — Realistic Practice, Real-Time Feedback</h3>
  <p align="center">
    Prepare smarter, not harder — with AI voice agents that simulate interviews and coach you like a pro. <br />
    Built with 🔥 modern tech, engineered for career success.
  </p>
</div>

---

## 📚 Table of Contents

1. [📌 Introduction](#introduction)
2. [🛠️ Tech Stack](#tech-stack)
3. [✨ Features](#features)
4. [🚀 Quick Start](#quick-start)

---

## <a name="introduction">🤖 Introduction</a>

**Prepwise** is an AI-powered platform that transforms how you prepare for job interviews. It leverages cutting-edge tools like **Vapi AI** voice agents and **Google Gemini** to conduct lifelike mock interviews, then gives you real-time feedback to level up your responses.

Whether you're a developer exploring AI integrations or a job seeker brushing up on your soft skills, Prepwise delivers a seamless, immersive, and _incredibly_ helpful experience — all built with **Next.js**, **Firebase**, **TailwindCSS**, and **shadcn/ui** components for a modern dev stack.

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- ⚡ **Next.js** — Fullstack React Framework
- 🔥 **Firebase** — Auth & Firestore
- 💨 **Tailwind CSS** — Utility-first styling
- 🧠 **Vapi AI** — Voice-driven AI agents
- 🧹 **shadcn/ui** — Headless UI Components
- 🧬 **Google Gemini API** — Context-aware AI responses
- 📏 **Zod** — Schema validation

---

## <a name="features">🔋 Features</a>

💡 **AI Voice Interviews**  
→ Simulate job interviews with natural, real-time conversations powered by Vapi AI + Gemini.

🔐 **Authentication**  
→ Sign up / sign in via Firebase — fast and secure.

🧑‍💼 **Personalized Feedback**  
→ Get context-rich insights and feedback from the AI after every session.

📄 **Live Transcripts**  
→ Every interview is transcribed and saved for review and reflection.

📊 **Smart Dashboard**  
→ Track your interviews, revisit feedback, and organize your prep.

🎨 **Modern UI/UX**  
→ Clean, responsive design powered by Tailwind and shadcn/ui — easy on the eyes, optimized for productivity.

📱 **Mobile-Friendly**  
→ 100% responsive — train anytime, from any device.

🔧 **Extensible Architecture**  
→ Modular, scalable codebase that’s easy to build on or customize.

---

## <a name="quick-start">⚡ Quick Start</a>

Follow these steps to run the project locally.

### ✅ Prerequisites

Ensure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

---

### 📦 Installation

Clone the repo:

```bash
git clone https://github.com/BernieTv/AI-Powered-Interviews.git
cd AI-Powered-Interviews
```

Install dependencies:

```bash
npm install
```

---

### 🔐 Environment Variables

Create a `.env.local` file in the root directory and add your credentials:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=""
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=""
NEXT_PUBLIC_FIREBASE_PROJECT_ID=""
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=""
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=""
NEXT_PUBLIC_FIREBASE_APP_ID=""
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=""

FIREBASE_PROJECT_ID=""
FIREBASE_PRIVATE_KEY=""

GOOGLE_GENERATIVE_AI_API_KEY=""

NEXT_PUBLIC_VAPI_WEB_TOKEN=""
NEXT_PUBLIC_VAPI_WORKFLOW_ID=""

NEXT_PUBLIC_BASE_URL="http://localhost:3000"
```

> Replace the placeholder values with your actual [Firebase](https://firebase.google.com/) and [Vapi](https://vapi.ai/) credentials.

---

### 🏁 Run the Dev Server

Start the development server:

```bash
npm run dev
```

Navigate to `http://localhost:3000` to experience the app.

---

## 💬 Contributing

Pull requests are welcome! Feel free to fork the repo and improve on it — whether it’s styling, adding a feature, or optimizing performance.

---
