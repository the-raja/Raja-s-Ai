# 💻 Raja Kumar - macOS AI Assistant Portfolio

An interactive, responsive macOS desktop simulation portfolio for **Raja Kumar**, Final-Year B.Tech CSE Student @ KIIT University specializing in **AI/ML, Generative AI, and Intelligent Systems**.

Built with **Next.js 16 (Turbopack)**, **React 19**, **TypeScript**, and **Tailwind CSS**, featuring an integrated **AI Assistant** powered by **Groq SDK** and **Llama 3.3 70B**.

---

## ✨ Features

- 🖥️ **macOS Desktop & Window System**: Draggable, resizable windows mimicking the macOS Sequoia desktop interface.
- 🤖 **Interactive AI Assistant**: Real-time streaming AI chatbot representation powered by Groq Llama 3.3 70B trained on Raja's background, projects, and skills.
- 💻 **Terminal App**: Interactive command line interface displaying technical skills across AI/ML, Languages, Frameworks, DevOps, and Core CS Fundamentals.
- 🌐 **Safari Browser Simulation**: Interactive web browser with mock search results, GitHub profile preview, and LinkedIn showcase.
- 📱 **Mobile & Desktop Responsive**: Custom standalone portfolio view optimized for mobile devices and full macOS workspace for desktop screens.
- ⚡ **Production Grade Build**: Fast server-side & static page generation using Next.js App Router and Turbopack.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router & Turbopack)
- **Frontend**: [React 19](https://react.dev/), TypeScript, Tailwind CSS
- **Animations & Interaction**: GSAP, React Draggable
- **AI & Backend**: Groq SDK (`llama-3.3-70b-versatile`), Next.js Route Handlers
- **Icons & Fonts**: Next.js Fonts (`Geist`, `Geist_Mono`), Custom SVG icons

---

## 🚀 Featured Projects

- **AI-Map**: Local RAG & Vector Database Platform built from scratch using HNSW, KD-Tree, and Brute Force search algorithms with Ollama integration and PCA visualization.
- **MIRAI**: Autonomous AI Combat System with NVIDIA ACE-inspired backend, FAISS vector retrieval, PyTorch/XGBoost ensemble inference, and Cognitive OS.
- **OmniAgent**: Multi-Agent System Framework designed for autonomous task execution, tool orchestration, and LLM reasoning workflows.

---

## ⚡ Getting Started Locally

### 1. Clone the Repository
```bash
git clone https://github.com/the-raja/portfolio.git
cd portfolio
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create a `.env.local` file in the root directory:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 4. Run the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 📦 Production Build & Deployment

To test a production build locally:
```bash
npm run build
npm run start
```

### Deploying on Vercel
1. Push your code to GitHub.
2. Import the repository into [Vercel](https://vercel.com).
3. Add `GROQ_API_KEY` under **Environment Variables** in Project Settings.
4. Deploy!

---

## 📬 Contact & Links

- **GitHub**: [the-raja](https://github.com/the-raja/)
- **LinkedIn**: [theraja](https://linkedin.com/in/theraja/)
- **LeetCode**: [the-raja](https://leetcode.com/u/the-raja/)
- **Email**: [rrajakkumar01@gmail.com](mailto:rrajakkumar01@gmail.com)
- **Portfolio**: [the-raja.vercel.app](https://the-raja.vercel.app/)
