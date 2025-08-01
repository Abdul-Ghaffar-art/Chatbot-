# Chatbot-# 🦙 LangChain Chatbot with Memory

A simple AI chatbot built using **LangChain**, **Streamlit**, and **Ollama**, powered by the `deepseek-r1:1.5b` model. The chatbot includes **chat memory**, **temperature control**, and the ability to **download conversation history**.

## 🚀 Features

- 🤖 AI Assistant with memory
- 🎚️ Adjustable temperature for model creativity
- 💾 Save and download chat history
- 🧠 Uses LangChain's prompt templates and output parser
- 🔒 Environment variables supported via `.env`

---

## 🛠️ Tech Stack

- [LangChain](https://github.com/langchain-ai/langchain)
- [Ollama](https://ollama.com/) (for local LLMs)
- [Streamlit](https://streamlit.io/)
- Python 3.10+

---

## 📦 Installation

```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
