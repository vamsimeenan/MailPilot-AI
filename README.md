# ✉️ MailPilot AI

> **Intelligent AI-Powered Email Generation Platform**  
> Generate professional, personalized, and context-aware cold emails instantly.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0.1+-green?style=for-the-badge&logo=chainlink&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red?style=for-the-badge&logo=streamlit&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-Enabled-orange?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_DB-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge)

---

## 📌 Overview

**MailPilot AI** is an advanced AI-powered email generation system that eliminates the friction of writing cold emails and professional outreach — manually.

By combining **Llama 3.1**, **LangChain**, **Groq API**, and **ChromaDB**, MailPilot generates highly personalized, tone-aware, and ready-to-send emails in seconds — all through a clean Streamlit interface.

---

## 🎯 Problem Statement

Writing cold emails at scale is:

- ⏳ **Time-consuming** — crafting each email from scratch
- 🔁 **Repetitive** — same structure, different details
- 🎭 **Inconsistent** — tone and quality vary
- 📉 **Hard to personalize** — at volume, quality drops

**MailPilot AI solves all of this.**

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🤖 AI Email Generation | Instant professional emails via Llama 3.1 |
| 🎭 Tone Customization | Formal, Casual, Professional, or Friendly |
| ⚡ Fast Inference | Low-latency responses powered by Groq API |
| 🧠 Prompt Engineering | Structured prompt pipeline for consistent quality |
| 📚 Context-Aware Output | ChromaDB retrieval-augmented generation (RAG) |
| 🎨 Clean UI | Interactive Streamlit interface — no setup friction |

---

## 🏗️ System Architecture
User Input
↓
Streamlit Frontend
↓
Prompt Engineering Layer
↓
LangChain Orchestration Pipeline
↓
ChromaDB Context Retrieval (RAG)
↓
Groq API → Llama 3.1
↓
Structured Email Output
---

## 🧠 How It Works

**Step 1 — User Input**  
Enter recipient details, purpose, tone, and any specific requirements.

**Step 2 — Prompt Processing**  
LangChain formats and optimizes the prompt for maximum LLM performance.

**Step 3 — Context Retrieval**  
ChromaDB retrieves relevant context to personalize the output.

**Step 4 — LLM Generation**  
Llama 3.1 via Groq API generates a polished, personalized email.

**Step 5 — Structured Output**  
The final email is displayed in the Streamlit UI — ready to copy and send.

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| Python | Core Backend |
| LangChain | LLM Orchestration |
| Groq API | Fast AI Inference |
| Llama 3.1 | Email Generation Model |
| ChromaDB | Vector Store / RAG |
| Streamlit | Frontend Interface |
| python-dotenv | Environment Management |

---

## 📂 Project Structure

MailPilot-AI/
│
├── app.py                  # Main application entry point
├── chains/                 # LangChain pipelines
├── prompts/                # Prompt templates
├── vectorstore/            # ChromaDB vector store
├── assets/                 # UI images and diagrams
│   ├── banner.png
│   ├── home.png
│   ├── interface.png
│   ├── output.png
│   └── architecture.png
│
├── requirements.txt
├── .env                    # API keys (not committed)
└── README.md
---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- A [Groq API Key](https://console.groq.com/)

### 1. Clone the Repository
```bash
git clone https://github.com/vamsimeenan/MailPilot-AI.git
cd MailPilot-AI
```

### 2. Create a Virtual Environment

**Windows**
```bash
python -m venv venv
venv\Scripts\activate
```

**Mac / Linux**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 5. Run the Application
```bash
streamlit run app.py
```

---

## 🎯 Use Cases

- **Cold outreach** to recruiters, clients, or collaborators
- **Professional follow-ups** after meetings or interviews
- **Business proposals** with a personalized touch
- **Networking emails** that don't feel generic

---

## 🔮 Roadmap

- [ ] Gmail Integration (send directly from the app)
- [ ] Email Scheduling
- [ ] Multi-language Support
- [ ] AI Signature Generator
- [ ] User Authentication & Email History
- [ ] Export to PDF
- [ ] Fine-Tuned Models for specific industries
- [ ] Real-time Collaboration Mode

---

## 📈 What I Learned Building This

- LLM Application Architecture end-to-end
- LangChain workflow and chain design
- Prompt Engineering for structured outputs
- Retrieval-Augmented Generation (RAG) with ChromaDB
- Groq API integration for low-latency inference
- Building and deploying Streamlit AI apps
- Vector database design and querying

---

## 👨‍💻 Author

**Vamsi Meenan Ravuri**  
AI • Full Stack • Software Engineering  
Passionate about building intelligent applications and scalable systems.

[![GitHub](https://img.shields.io/badge/GitHub-vamsimeenan-black?style=flat&logo=github)](https://github.com/vamsimeenan)

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push and open a Pull Request

---

## ⭐ Support

If MailPilot AI was useful to you:

- ⭐ **Star** the repository
- 🍴 **Fork** and build on top of it
- 📢 **Share** with others in the AI/dev community

---

## 📜 License

This project is developed for **educational and portfolio purposes**.

---

*Built with curiosity, caffeine, and a lot of prompt iterations. 🚀*
