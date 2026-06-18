# Carrer-Advisor-Chatbot
A domain-specific AI chatbot built with Ollama and Python that acts as a Career Advisor — restricted to career-related topics using system prompts and conversational memory.

 🎯 CareerBot — AI Career Advisor Chatbot

A domain-specific conversational AI chatbot built using **Ollama** and **Python**, designed to act exclusively as a professional Career Advisor. This project demonstrates core AI concepts including system prompts, conversational memory, and domain restriction using a locally-run LLM (Llama 3 / Phi-3).

📋 Overview

CareerBot is a terminal-based chatbot that helps users with:
- Resume and cover letter writing
- Job search strategies
- Interview preparation
- Career transitions
- Salary negotiation
- Professional skill development

The chatbot is strictly restricted to career-related topics. If asked about anything outside this domain (e.g., cooking, medical advice, sports), it politely declines and redirects the conversation back to career guidance.

 🛠️ Tech Stack

- **Python 3** — core application logic
- **Ollama** — running LLMs locally (Llama 3 / Phi-3)
- **System Prompts** — domain restriction and persona control

⚙️ Features

- ✅ Domain-restricted conversation (Career Advisor only)
- ✅ Multi-turn conversational memory
- ✅ Runs entirely locally — no external API costs
- ✅ Simple, readable Python implementation
- ✅ Easily adaptable to other domains (Doctor, Tutor, etc.)

🚀 Getting Started

Prerequisites
- [Anaconda](https://www.anaconda.com/download)
- [Ollama](https://ollama.com)

Installation

1. Pull a model:
```bash
   ollama run llama3
   # or, for lighter systems:
   ollama run phi3
```

2. Install the Python dependency:
```bash
   pip install ollama
```

3. Run the chatbot:
```bash
   python career_advisor_chatbot.py
```

## 💬 Usage

Simply type your career-related question after the `You:` prompt. Type `exit` to quit, or `clear` to reset the conversation.
