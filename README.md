📘 Study Mode Tutor

This project contains everything you need to run your **AI-powered study assistant** locally. It provides interactive tutoring features like chat, quizzes, PDF uploads, and assignment support — powered by the **Gemini API**.

---

## Features
- 🤖 **AI Tutor** – Ask questions and get instant answers  
- 📄 **PDF Uploads** – Summarize and explain study materials  
- 🧩 **Interactive Quizzes** – Auto-generate practice questions  
- 📝 **Assignment Helper** – Guided support for homework tasks  
- 📊 **Progress Review** – Track and review your learning progress  
- 🎨 **Custom Themes** – Light/Dark mode toggle  

---

##  Prerequisites

Make sure you have installed:

- **Node.js** (v16 or later)  
- **npm** or **yarn**  
- **Gemini API Key** → get one from [Google AI](https://ai.google.dev/)  

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/study-mode-tutor.git
cd study-mode-tutor
npm install


Create a `.env.local` file in the project root and add your Gemini API key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

---

## ▶️ Run Locally

Start the development server:

```bash
npm run dev
```

Then open the app in your browser at:  
👉 http://localhost:5173

---

## 📂 Project Structure

```
study-mode-tutor/
│── App.tsx               # Main application entry
│── index.tsx             # React bootstrap
│── components/           # UI components
│   ├── Sidebar.tsx
│   ├── ChatView.tsx
│   ├── PdfUpload.tsx
│   ├── QuizView.tsx
│   └── assignment/
│       └── AssignmentView.tsx
│── services/             # API integration
│   └── geminiService.ts
│── hooks/                # Custom hooks
│   └── useTheme.ts
│── package.json          # Dependencies & scripts
│── tsconfig.json         # TypeScript config
│── vite.config.ts        # Build config
│── .env.local            # Environment variables
```

## 🤝 Contributing

Contributions are welcome!  
You can extend this project by:  
- Adding new quiz types  
- Enhancing PDF parsing  
- Improving assignment workflows  

---

## 📜 License

This project is licensed under the **MIT License**.  
