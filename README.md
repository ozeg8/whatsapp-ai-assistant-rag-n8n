# 🤖 WhatsApp AI Assistant — n8n + Evolution API

A 24/7 AI-powered WhatsApp assistant that remembers every customer — forever.
Built for businesses that want smart, scalable, and affordable automation.

---

## ✨ Features
- 🧠 Long-term memory per customer (PostgreSQL + PGVector)
- 🎙️ Voice message transcription (OpenAI Whisper)
- 📁 Knowledge base via Google Drive
- 💬 Human-like responses with custom business persona
- 💰 Cost-efficient — Evolution API instead of WhatsApp Business API

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| n8n | Workflow automation |
| Evolution API | WhatsApp layer |
| PostgreSQL + PGVector | Memory & vector search |
| OpenAI GPT-4o | Language model |
| OpenAI Whisper | Voice transcription |
| Google Drive | Knowledge base storage |

## 🚀 Setup
1. Install n8n
2. Import `testwp_bot_clean.json`
3. Set your credentials (OpenAI, Postgres, Evolution API, Google Drive)
4. Connect your Evolution API webhook
5. Run the Google Drive loader to populate the vector store

## 📬 Contact
Built by [Your Name](https://linkedin.com/in/yourprofile)
