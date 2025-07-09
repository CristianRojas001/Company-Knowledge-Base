# Company Knowledge Base – AI-Driven Semantic Search (Supabase)

> Automated ingestion of documents → embedding → semantic‐searchable DB → Slack RAG agent.

---

## 🚀 Overview

1. **Watch** a Google Drive folder for new PDFs/CSVs.  
2. **Download** & **extract** text.  
3. **Generate** metadata (title & description) via Google Gemini.  
4. **Chunk** text, **embed** chunks with OpenAI, and **index** in Supabase Vector Store.  
5. **Slack Agent** listens for queries and returns context‐aware answers.

---

## 🔧 Prerequisites

- Docker & Docker Compose  
- ngrok (for local SSL tunnel)  
- A Google Cloud project with Drive + Gemini (PaLM) enabled  
- OpenAI API key  
- Supabase project with `Company Knowledge Base` table & `match_documents` function  
- Slack workspace & Incoming Webhook for notifications  

---

## 🏗️ Local Setup

1. **Clone** this repo:
   ```bash
   git clone https://github.com/your-user/n8n-workflows.git
   cd n8n-workflows
