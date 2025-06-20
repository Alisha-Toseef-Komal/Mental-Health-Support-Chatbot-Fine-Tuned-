
# 🧠 Mental Health Support Chatbot

This project is a supportive chatbot built for mental wellness conversations. It uses a free, offline large language model (LLM) called **GODEL-v1_1-base-seq2seq** developed by Microsoft, which responds with empathy and encouragement.

## 🎯 Objective
To build a chatbot that provides gentle, supportive, and emotionally aware responses to users experiencing stress, anxiety, or emotional difficulties.

## 🧰 Tools & Technologies
- Python 3.x
- Hugging Face Transformers library
- Pretrained model: `microsoft/GODEL-v1_1-base-seq2seq`

## 🌐 Model Info
- Source: Hugging Face 🤗
- Works offline (no API key needed)
- Prompt engineered to simulate empathy

## 💡 Features
- CLI chatbot (works in terminal)
- Empathetic responses using LLM
- No need for OpenAI or Hugging Face tokens

## 📦 Installation

```bash
pip install transformers sentencepiece
```

## 🚀 How to Run

1. Run the chatbot script.
2. Enter mental health-related questions or feelings (e.g., "I feel anxious", "I'm stressed about exams").
3. The bot replies with kind and supportive responses.

## 📝 Example Interaction

```
You: I feel very anxious.
Bot: I'm really sorry you're feeling this way. You're not alone, and I'm here for you.

You: I'm overwhelmed with my studies.
Bot: That sounds difficult. Be kind to yourself and take things one step at a time.
```

## 🛡️ Disclaimer
This chatbot is **not a replacement for professional help**. It is designed for **educational purposes only** and should not be used in place of real mental health support.

## 🗂️ Files Included
- `mental_health_chatbot.py` – Python chatbot script using GODEL
- `README.md` – This documentation file

---
