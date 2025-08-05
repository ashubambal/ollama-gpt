# 🧠 Ollama-GPT — Self-Hosted Private LLM with Open WebUI

Run your own **ChatGPT-like interface** entirely offline using:
- **[Ollama](https://ollama.com/)** — Run AI models locally on your own machine.
- **[Open WebUI](https://github.com/open-webui/open-webui)** — Beautiful ChatGPT-style interface.

> ⚡ **Privacy-first**: No API keys, no data sharing — 100% offline.

---

## 📦 Features
- 🚀 Run open-source LLMs locally (LLaMA, CodeLLaMA, Qwen, Phi, etc.)
- 🔒 Fully private — your data stays on your machine
- 🐳 Docker-based setup for quick deployment
- 💻 CLI or Web UI access
- ⚙ Configurable CPU & RAM limits

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ashubambal/ollama-gpt.git
cd ollama-gpt

### 2️⃣ Configure Environment Variables
Edit docker-compose.yml and set your own WEBUI_SECRET_KEY:
```bash
WEBUI_SECRET_KEY=enter-your-secret-key


