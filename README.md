# Mini Cursor AI IDE 🎨💻
Mini Cursor AI IDE — an AI-powered playground that transforms your prompts into runnable apps with live preview and token tracking
A lightweight **AI-powered IDE** built with Node.js, Express, Gemini AI, and Langfuse.  
Ask it to **build anything** (games, dashboards, visual demos) → it generates runnable files (`index.html`, `style.css`, `main.js`) that you can preview instantly.

---

## ✨ Features
- 🔥 Natural language → runnable code (HTML, CSS, JS)
- 📊 Token tracking + observability with **Langfuse**
- 🎮 Create games, dashboards, animations, apps
- 🖥️ Visual preview (like a mini version of Cursor IDE)

---

## 🚀 Getting Started

### 1. Clone repo
```bash
git clone https://github.com/YOUR-USERNAME/mini-cursor-ai-ide.git
cd mini-cursor-ai-ide

2. Install dependencies
npm install

3. Configure environment

Create .env from example:

cp .env.example .env

Add your keys:

LANGFUSE_HOST=https://hipaa.cloud.langfuse.com
LANGFUSE_PUBLIC_KEY=pk-xxxx
LANGFUSE_SECRET_KEY=sk-xxxx
GOOGLE_API_KEY=AIzaSyXXXX

4. Run server
npm start
Server runs at → http://127.0.0.1:5000

🛠 Example Prompts

Create a responsive calculator

Build a personal dashboard with weather, clock, todo list, and mini calculator

Make a neon snake game with smooth animations and score tracking

Create an animated sales dashboard with charts and filters
