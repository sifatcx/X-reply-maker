# NovaReply AI — 100% Serverless Edition

A standalone, serverless Chrome Extension for X (formerly Twitter). Runs **100% inside your browser** without requiring any backend, server, or cloud hosting.

---

## ⚡ Highlights

- **Zero Backend Required**: Directly calls AI provider APIs from the browser via HTTPS.
- **Works Instantly in Chrome Web Store**: Users simply install the extension, add their API key, and start generating replies immediately.
- **Zero Hosting Costs**: No Railway, Docker, or VPS bills.
- **Client-Side AES-GCM Encryption**: API keys are encrypted at rest locally in `chrome.storage.local` and never touch any third-party database.
- **Local Generation History**: View past replies and latency directly on the extension's Dashboard without an external database.
- **Multi-Provider Support**:
  - **Groq** (Recommended for speed, e.g. `llama-3.3-70b-versatile`)
  - **Google Gemini** (`gemini-2.0-flash`)
  - **OpenAI** (`gpt-4.1-mini`, `gpt-4o`)
  - **Anthropic Claude** (`claude-3-5-haiku-20241022`)
  - **DeepSeek** (`deepseek-chat`)
  - **OpenRouter** (`openai/gpt-4.1-mini`, etc.)
  - **Local Ollama** (`http://localhost:11434`)
  - **Local LM Studio** (`http://localhost:1234`)

---

## 🛠️ Testing Locally in Chrome

1. Open Chrome and navigate to:
   ```text
   chrome://extensions
   ```
2. Enable **Developer mode** (toggle in the top-right corner).
3. Click **"Load unpacked"** (top-left).
4. Select the `extension-serverless` folder in this repository:
   ```text
   c:\Users\SIFAT\3D Objects\Automation\extension-serverless
   ```
5. Click the NovaReply AI icon in your Chrome toolbar -> Click **Settings**.
6. Select your preferred AI provider (e.g. Groq or OpenAI), paste your API key, and click **"Test Key"** to verify connection.
7. Open [x.com](https://x.com), click on any post composer, and press <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>G</kbd>!

