<div align="center">

# 🔨 BrowserForge

**A zero-install AI coding IDE that runs entirely in your browser.**

Connect any LLM — OpenAI, Gemini, Ollama, or any OpenAI-compatible API — and let an autonomous agent read, write, delete, and rename files in your local workspace. No server. No backend. No tracking.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
![Single File](https://img.shields.io/badge/Size-Single%20HTML%20File-orange)

[**→ Try it now (GitHub Pages)**](#getting-started) · [Report Bug](../../issues) · [Request Feature](../../issues)

</div>

---

## ✨ What is this?

BrowserForge is a **single HTML file** that turns your browser into a full AI-powered IDE:

- 📂 **Mount any local folder** via the File System Access API
- 🤖 **Connect any LLM** (Gemini, GPT-4o, Ollama, LM Studio, etc.)
- ✍️ **Autonomous file operations** — the AI writes, modifies, deletes & renames files
- 📊 **Excel & Word support** — read/modify `.xlsx` and `.docx` files
- 🖼️ **Vision support** — send images to multimodal models
- 🎤 **Voice input** — dictate prompts in German/English
- 🔒 **100% client-side** — nothing leaves your browser unless you send it to an API

No npm. No build step. No Docker. Just open the HTML file.

---

## 🚀 Getting Started

### Option 1: Just open it
```bash
git clone https://github.com/YOUR_USERNAME/BrowserForge.git
cd BrowserForge
# Open index.html in Chrome/Edge (Firefox doesn't support File System Access API)
