# 🤖 n8n Gemini Chatbot Agent

A simple AI Chatbot Agent built using **n8n**, **Google Gemini AI**, and **Simple Memory**. This workflow receives user messages, processes them with Gemini, remembers previous conversations, and returns intelligent responses.

## 🚀 Features

* 💬 AI Chat Interface
* 🧠 Conversation Memory
* 🤖 Google Gemini Integration
* ⚡ Built using n8n (No-Code Automation)
* 🔄 Easy to Import and Customize

## 🛠️ Technologies Used

* n8n
* Google Gemini API
* AI Agent Node
* Simple Memory Node

## 📂 Workflow

```text
Chat Trigger
      │
      ▼
  AI Agent
   │     │
   │     ├── Google Gemini Chat Model
   │
   └───── Simple Memory
```

## 📸 Project Overview

The workflow performs the following steps:

1. Receives a chat message.
2. Sends the message to the AI Agent.
3. Uses Google Gemini to generate a response.
4. Stores conversation history using Simple Memory.
5. Returns the AI-generated reply.

## 📦 Installation

1. Install n8n.
2. Open the n8n Editor.
3. Import the `1st_chatbot_agent.json` workflow.
4. Add your Google Gemini API credentials.
5. Activate the workflow.
6. Start chatting with the AI Agent.

## 📁 Project Structure

```
n8n-gemini-chatbot-agent/
│
├── 1st_chatbot_agent.json
├── README.md
└── LICENSE (Optional)
```

## 🔑 Prerequisites

* n8n installed
* Google Gemini API Key
* Internet Connection

## ▶️ Usage

* Import the workflow into n8n.
* Configure Gemini credentials.
* Activate the workflow.
* Send a message through the chat trigger.
* Receive AI-generated responses with conversation memory.

## 🤝 Contributing

Feel free to fork this repository, improve the workflow, and submit pull requests.

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, don't forget to star the repository!
