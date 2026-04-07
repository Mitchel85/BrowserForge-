# BrowserForge 🔨

BrowserForge is a zero-setup, local AI IDE and Native Web Agent that runs entirely in your browser. It allows you to mount a local workspace, edit code, view documents, and leverage various flagship AI models to autonomously perform file operations right on your machine.

## ✨ Features
* **Zero Backend:** Runs 100% locally in your browser using the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_API).
* **Multi-Provider AI:** Built-in support for OpenAI, Google Gemini, Anthropic Claude, xAI, Mistral, DeepSeek, local models via Ollama/LM Studio, and more.
* **Smart File Editor:** Integrated [Monaco Editor](https://microsoft.github.io/monaco-editor/) with syntax highlighting and code formatting.
* **Document Support:** Preview images, read Excel (`.xlsx`) files, and parse Word (`.docx`) documents natively.
* **Voice Dictation:** Speak your prompts directly to the agent.
* **Privacy First:** Your API keys are strictly used on the client side and never sent to a third-party server besides the AI provider.

## 🚀 How to Use
1. Clone the repository or simply open `index.html` in a modern browser (Chrome/Edge recommended for File System API support).
2. Click **Mount Workspace** and select a local folder to work in.
3. Configure your preferred **Provider Preset**, model, and API Key in the top navigation bar.
4. Open a file from the left sidebar or prompt the agent in the bottom chat area to create, modify, or delete files autonomously!

## 🛠️ Tech Stack
* HTML5 / Vanilla JavaScript
* [Tailwind CSS](https://tailwindcss.com/)
* [Monaco Editor](https://microsoft.github.io/monaco-editor/)
* [Marked.js](https://marked.js.org/)
* SheetJS (XLSX) & Mammoth.js (DOCX)
