# blog-writing-ai-agent

# 🧠 AI Blog Writing Agent (LangGraph + Gemini + Streamlit)

An advanced multi-agent AI system that automatically generates structured, high-quality technical blog posts using **LangGraph**, **Google Gemini**, **Tavily API**, and **Streamlit**.

---

## 🚀 Features

- 🔀 Multi-Agent Workflow using LangGraph
  - Router → Research → Orchestrator → Workers → Reducer
- 🌐 Web Research Integration (Tavily API)
- 🧠 Structured Planning with Pydantic
- ✍️ Parallel Section-wise Blog Generation
- 📄 Automatic Markdown (.md) export
- ⚡ Streamlit UI for easy interaction
- 🧩 Supports:
  - Explainer Blogs
  - Tutorials
  - Comparisons
  - System Design
  - News Roundups

---


---

## 🧠 How It Works

### 1. Router
- Decides whether research is needed:
  - `closed_book`
  - `hybrid`
  - `open_book`

---

### 2. Research Node
- Uses Tavily API
- Collects relevant web data
- Extracts structured evidence

---

### 3. Orchestrator
- Creates structured blog plan:
  - 5–9 sections
  - Goals
  - Bullet points
  - Word targets

---

### 4. Worker Nodes
- Each worker writes one section
- Supports:
  - Code snippets
  - Citations
  - Technical depth

---

### 5. Reducer
- Merges all sections
- Generates final Markdown blog
- Saves `.md` file

---

## 🛠️ Tech Stack

- LangGraph
- LangChain
- Google Gemini API
- Tavily Search API
- Streamlit
- Pydantic

---
UI
<img width="951" height="941" alt="Screenshot 2026-05-10 120956" src="https://github.com/user-attachments/assets/15a9f675-a964-4dc4-8d78-0b82411168d9" />

