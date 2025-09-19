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

📂 Project Structure

mini-cursor-ai-ide/

├── server.js         # Express backend

├── tools.js          # Gemini + Langfuse integration

├── index.html        # Frontend IDE UI

├── style.css

├── main.js

├── .env.example      # Environment variables template

└── README.md


🖤 Credits

Google Gemini


Langfuse

Inspired by Cursor IDE

## 🚀 Getting Started

### 1. Clone repo

# 1. Clone the repo
git clone https://github.com/Varsha-salimath/mini-cursor-ai-ide.git
cd mini-cursor-ai-ide

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env

# Create a .env file in the project root with:
LANGFUSE_HOST=your_langfuse_url
LANGFUSE_PUBLIC_KEY=your_public_key
LANGFUSE_SECRET_KEY=your_secret_key
GOOGLE_API_KEY=your_google_api_key

# 4. Run the development server
npm start

# 5. Open the app
