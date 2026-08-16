# Autonomous AI Operations Agent 🤖

An AI-powered conversational automation agent built with **n8n**, designed to process incoming messages, maintain conversational context, and trigger automated notifications and actions.

---

## 🌟 Key Features

- **Intelligent Chat Handling:** Processes incoming user messages using an AI Agent powered by an OpenRouter Chat Model.

- **Conversational Memory:** Maintains conversational context using a Simple Memory component.

- **Automated Actions:** Connects the AI Agent to external tools to trigger actions based on the workflow requirements.

- **Telegram Alerts:** Sends automated notifications through a connected Telegram bot.

- **Web Push Notifications:** Supports event-triggered Web Push notifications.

---

## 🛠️ Tech Stack

- **Workflow Orchestration:** [n8n](https://n8n.io/)
- **AI Model:** OpenRouter Chat Model
- **Agent:** n8n AI Agent
- **Memory:** Simple Memory
- **Notifications:** Telegram Bot & Web Push Notifications

---

## 🔄 Workflow Architecture

```text
Incoming Chat Message
          ↓
      AI Agent
          ↓
   OpenRouter LLM
          +
     Simple Memory
          ↓
    Agent Decision
       ↙       ↘
 Telegram     Web Push
 Notification Notification
  
    
      
     
      
       
        

        
            
