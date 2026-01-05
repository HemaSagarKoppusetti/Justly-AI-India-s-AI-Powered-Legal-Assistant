# Justly AI  
### India’s AI-Powered Legal Assistant 🇮🇳⚖️

**Justly AI** is an intelligent, conversational legal assistant built to simplify access to **Indian legal knowledge** using **Artificial Intelligence**. It enables users to ask legal questions in natural language (text or voice) and receive **clear, contextual, and easy-to-understand legal guidance**.

This project aims to bridge the gap between complex legal systems and everyday citizens, law students, and professionals by leveraging modern web technologies and large language models.

---

## 🌟 Vision

Access to legal information should be **simple, fast, and inclusive**.  
Justly AI envisions a future where anyone can understand their rights and legal options without barriers such as language, complexity, or cost.

---

## 🚀 Key Features

### 🧠 AI-Powered Legal Intelligence
- Natural language legal Q&A tailored to **Indian laws**
- Context-aware responses for legal scenarios
- Simplified explanations for complex legal terms

### 💬 Conversational Interface
- Interactive **chat-based UI**
- Clean, minimal, and user-friendly experience

### 🎙️ Voice Support
- Speech-to-Text (STT) for voice-based queries
- Text-to-Speech (TTS) for audio responses
- Accessibility-focused design

### 🌐 Multilingual Capability (Scalable)
- English-first implementation
- Designed to support Indian languages (Hindi, Telugu, Tamil, etc.)

### ☁️ Cloud-Native Architecture
- Scalable hosting and backend services
- Secure API handling and configuration

---

## 🛠️ Technology Stack

This project is built using a modern, scalable, and production-ready technology stack:

### 🎨 Frontend
- **Next.js** – React framework for server-side rendering and routing
- **React.js** – Component-based UI development
- **TypeScript** – Type safety and maintainable code
- **Tailwind CSS** – Utility-first styling for rapid UI development

### 🧠 AI & Language Models
- **Large Language Models (LLMs)** for legal reasoning and responses
- **Prompt Engineering** for Indian legal context
- Future-ready for **RAG (Retrieval Augmented Generation)** integration

### 🔊 Voice & Accessibility
- **Web Speech API**
  - Speech-to-Text (STT)
  - Text-to-Speech (TTS)

### 🔧 Backend & APIs
- **Node.js**
- **Next.js API Routes** for serverless backend logic
- Secure API key handling via environment variables

### ☁️ Cloud & Deployment
- **Firebase**
  - Firebase Hosting
  - Cloud Functions (if enabled)
- Scalable, serverless deployment model

### 🗂️ Data Handling
- Session-based conversational flow
- Designed to integrate:
  - Firestore / NoSQL databases
  - Vector databases for embeddings (future scope)

### 🧪 Developer Tooling
- **ESLint** – Code linting
- **Prettier** – Code formatting
- **Git & GitHub** – Version control and collaboration

---

## 📂 Project Structure

```text
Justly-AI-India-s-AI-Powered-Legal-Assistant/
│
├── src/
│   ├── app/              # Next.js app router & pages
│   ├── components/       # Reusable UI components
│   ├── lib/              # Utility functions & API helpers
│   ├── styles/           # Global styles
│
├── public/               # Static assets
├── firebase.json         # Firebase configuration
├── package.json          # Dependencies & scripts
├── .env.local            # Environment variables
└── README.md


---

## 🧑‍💻 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/HemaSagarKoppusetti/Justly-AI-India-s-AI-Powered-Legal-Assistant.git
cd Justly-AI-India-s-AI-Powered-Legal-Assistant
npm install
OPENAI_API_KEY=your_api_key_here
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_domain
npm run dev
npm run build
firebase deploy
