# Gemini Code Reviewer

An AI-powered web application that automatically reviews public GitHub repositories, generates detailed feedback, visual documentation, and provides an interactive AI assistant for codebase exploration. Powered by Google Gemini AI.

---

## 🚀 Features

- **Automated Code Review:**
  - Enter any public GitHub repository URL and get a comprehensive code review powered by Google Gemini AI.
- **Architectural Summary:**
  - Get a technical summary of the project’s architecture, frameworks, and structure.
- **Actionable Feedback:**
  - Receive a synthesized report with bugs, best practices, and improvement suggestions.
- **Visual Documentation:**
  - Auto-generates architecture diagrams, dependency graphs, flowcharts, and class diagrams using Mermaid.js.
- **AI Chat Assistant:**
  - Chat with "DeepWiki", an AI assistant that answers questions about the analyzed codebase and diagrams.
- **Relevant Repo Recommendations:**
  - Get suggestions for similar or relevant repositories based on your project.

---

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Tailwind CSS
- **Build Tool:** Vite
- **AI:** Google Gemini AI (`@google/genai`)
- **Diagrams:** Mermaid.js
- **Data Source:** GitHub REST API

---

## 📦 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- A [Google Gemini API Key](https://aistudio.google.com/app/apikey)

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up your Gemini API key:**
   - Create a file named `.env.local` in the root directory.
   - Add your Gemini API key:
     ```env
     GEMINI_API_KEY=your-gemini-api-key-here
     ```

4. **Run the app locally:**
   ```sh
   npm run dev
   ```
   The app will be available at [http://localhost:5173](http://localhost:5173) (or as indicated in your terminal).

---

## 🖥️ Usage

1. Open the app in your browser.
2. Enter a public GitHub repository URL (e.g., `https://github.com/facebook/react`).
3. Click **Analyze** to start the review process.
4. View the generated report, diagrams, and chat with the AI assistant for deeper insights.

---

## 📊 Example Output

- **Code Review Report:**
  - Executive summary, bugs, best practices, and recommendations.
- **Visual Documentation:**
  - Architecture diagram, dependency graph, flowchart, class diagram (all in Mermaid.js).
- **AI Chat:**
  - Ask questions like "What is the main architecture?", "Show me the data flow", or "Are there any security issues?"

---

## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests for improvements, bug fixes, or new features.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

---

## 📄 License

MIT License. See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- [Google Gemini AI](https://aistudio.google.com/)
- [Mermaid.js](https://mermaid-js.github.io/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)
- [GitHub](https://github.com/)
