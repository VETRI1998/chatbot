# 💬 Django WebSocket Chatbot

A simple yet interactive AI chatbot built using **Django**, **Channels**, and **WebSockets**. This bot can respond to questions related to general knowledge, computer science, and mental health using a built-in dataset.

### 🚀 Live Demo
Hosted on Render: [https://chat-bot-5wea.onrender.com](https://chat-bot-5wea.onrender.com)

---

## 📌 Features

- Real-time chat with WebSocket support
- Categorized question suggestions (General, Computer, Mental Health)
- Clean and responsive UI
- Fuzzy matching logic to handle similar questions
- Hosted on Render using Daphne ASGI server

---

## 🛠️ Tech Stack

- **Backend**: Django, Channels, Daphne
- **Frontend**: HTML, CSS, Vanilla JavaScript
- **WebSocket**: Django Channels
- **Deployment**: Render
- **Language**: Python 3.11+

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/chatbot_project.git
cd chatbot_project
---
2. Create virtual environment and activate
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
```bash
pip install -r requirements.txt

4. Run the development server
```bash
daphne -b 0.0.0.0 -p 8000 chatbot_project.asgi:application
