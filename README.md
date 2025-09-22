# 📘 Study Mode Tutor

This project contains everything you need to run your **AI-powered study assistant** locally. It provides interactive tutoring features like chat, quizzes, PDF uploads, assignment support, and **progress review** — powered by the **Gemini API**.

---

## ✨ Features

- 🤖 **AI Tutor** – Ask questions and get instant answers  
- 📄 **PDF Uploads** – Summarize and explain study materials  
- 🧩 **Interactive Quizzes** – Auto-generate practice questions  
- 📝 **Assignment Helper** – Guided support for homework tasks  
- 📊 **Progress Review** – Track and review your learning progress  
- 🎨 **Custom Themes** – Light/Dark mode toggle  

---

## 🔧 Prerequisites

Make sure you have installed:

- **Node.js** (v16 or later)  
- **npm** or **yarn**  
- **Gemini API Key** → get one from [Google AI](https://ai.google.dev/)  

---

## 🚀 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/studymodetutor.git
cd studymodetutor
npm install
```

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
studymodetutor/
│── App.tsx               # Main application entry
│── index.tsx             # React bootstrap
│── components/           # UI components
│   ├── Sidebar.tsx
│   ├── ChatView.tsx
│   ├── PdfUpload.tsx
│   ├── QuizView.tsx
│   ├── ProgressReview.tsx   # (new) Review My Progress feature
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

---

## 💡 Example Usage

### Ask a Study Question
```
"What are the main causes of World War I?"
```

### Generate a Quiz
```
"Create a 5-question multiple choice quiz about World War I"
```

### Work with a PDF
1. Upload your study material (PDF)  
2. Ask:  
```
"Summarize the key points from Chapter 2"
```

### Review Your Progress
```
"Show me a summary of my study progress this week"
```

---

## ⚠️ Troubleshooting

- **Missing GEMINI_API_KEY** → Check your `.env.local` file  
- **Port in use** → Change default port in `vite.config.ts`  
- **Dependency errors** → Run `npm install` again  

---

## 📦 Dependencies

| Package       | Purpose                   |
|---------------|---------------------------|
| React         | UI framework              |
| TypeScript    | Type safety               |
| Vite          | Development/build tool    |
| dotenv        | Environment variables     |
| @google/genai | Gemini API client         |
| pdfjs-dist    | PDF parsing & rendering   |

---

## 🤝 Contributing

Contributions are welcome!  
You can extend this project by:  
- Adding new quiz types  
- Enhancing PDF parsing  
- Improving assignment workflows  
- Expanding progress tracking  

---

## 📜 License

This project is licensed under the MIT License.  
