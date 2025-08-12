# mvnifest AI Bot 🤖⚡

[![n8n](https://img.shields.io/badge/Powered%20by-n8n-13BAA8)](https://n8n.io) 
[![Telegram](https://img.shields.io/badge/Telegram-Bot-2CA5E0)](https://core.telegram.org/bots)

An intelligent Telegram bot powered by n8n with natural language interactions and flexible automation capabilities.

## 🌟 Key Features
- **Full-featured chatbot** (Desktop/Mobile)
- **Visual workflow control** via n8n
- **Dynamic response scenarios**
- **Easy API integration**

## 🖼️ Screenshots
<div align="center">

| Telegram Desktop | Telegram Mobile | n8n Workflow |
|------------------|-----------------|--------------|
| <img src="screenshots/telegram-desktop.jpg" width="250"> | <img src="screenshots/telegram-mobile.jpg" width="250"> | <img src="screenshots/n8n-workflow.png" width="250"> |

</div>

## ⚙️ Tech Stack
- **Core**: n8n (v1.0+)
- **Integrations**:
  - Telegram Bot API
  - Custom Webhooks
- **Hosting**: Ngrok/VPS

## 🚀 Quick Start
1. Clone this repo
2. Import `manifest-bot.json` to n8n
3. Configure:
   ```env
   TELEGRAM_TOKEN=your_bot_token
   N8N_WEBHOOK_URL=your_webhook
