# 📦 WhatsApp-Driven Google Drive Assistant (n8n)

## ✅ Features
- 🔗 WhatsApp + Twilio Sandbox
- 📁 Google Drive integration with OAuth2
- 🤖 GPT-4o summarization
- 🛡️ Delete confirmation guard
- 📊 Logging to Google Sheets

## 📦 Requirements
- Twilio WhatsApp Sandbox
- Google OAuth2 Credentials
- OpenAI API Key
- Docker (n8n container)

## 🧪 Supported Commands
- `LIST /Project`
- `DELETE /Project/report.pdf`
- `MOVE /A/file.txt /B`
- `SUMMARY /Project`

## 🚀 Deployment
1. Clone repo
2. Run `docker-compose up`
3. Set up Twilio webhook to `https://<your-url>/webhook/whatsapp-in`
4. Import `workflow.json` in n8n
