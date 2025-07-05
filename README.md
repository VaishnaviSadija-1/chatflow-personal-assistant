# 🤖 AI WhatsApp Assistant: Automate Your Life with n8n

A smart, no-code automation system built with **n8n** that transforms WhatsApp into your **AI-powered personal assistant**. From sending emails and managing your calendar to searching the web and storing memory — all via simple WhatsApp messages.

---

## ✨ Key Capabilities

### 💬 Chat-Based Assistant (WhatsApp Trigger)
- Connects with WhatsApp via webhook (e.g., **360dialog**, **Meta Cloud API**, or **Twilio**)
- Understands your queries and performs actions accordingly

### 📧 Smart Email Handling
- Automatically **send, fetch, or reply to emails** using Gmail
- Supports personalized responses through WhatsApp commands

### 📅 Calendar Control at Your Fingertips
- Create, update, or delete Google Calendar events via chat
- Get event summaries or reminders right from WhatsApp

### 🌐 Real-Time Web Search
- Leverages **Perplexity AI** to perform intelligent web searches
- Delivers summaries or answers back to your WhatsApp

### 🧠 Persistent Memory System
- Integrates with **Zep vector database**
- Stores previous interactions and recalls context for follow-ups

---

## 🧩 Tech Stack Overview

- **n8n** — Low-code automation platform
- **WhatsApp API** — via 360dialog / Meta Cloud / Twilio
- **Gmail API** — for email automation
- **Google Calendar API** — event management
- **Perplexity AI API** — intelligent search
- **Zep Vector DB** — long-term memory storage

---

## ⚙️ How the Workflow Operates

1. A message is received on WhatsApp (e.g., _"Get unread emails"_)
2. The webhook triggers n8n and passes the input
3. n8n parses the message and determines the right action
4. It executes the task: sends emails, fetches calendar info, or performs a web search
5. A human-like reply is sent back to WhatsApp
6. The interaction is stored in Zep for future memory/context

---

## 🔐 API Credentials Required

| Service          | Auth Type   | Get From                            |
|------------------|-------------|-------------------------------------|
| WhatsApp API     | Bearer Token| 360dialog / Meta Developer Portal  |
| Gmail API        | OAuth2      | Google Cloud Console               |
| Calendar API     | OAuth2      | Google Cloud Console               |
| Perplexity AI    | API Key     | Perplexity API Docs                |
| Zep Vector DB    | API Key     | Zep Docs                           |

---


### 🖼️ Screenshots  
![Workflow Overview](./screenshots/workflow-overview.png)  
![WhatsApp Chat](./screenshots/whatsapp-chat.png)

