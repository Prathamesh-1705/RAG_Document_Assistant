<div align="center">

# 📚 RAG Document Assistant

### AI-Powered Multi-Document Intelligence Platform

Upload PDFs, Word Documents, PowerPoint, CSV & Excel files and chat with them using Retrieval-Augmented Generation (RAG), Semantic Search, Hybrid Retrieval, AI Agents and Local Machine Learning.

# 🚀 Overview

RAG Document Assistant is a **full-stack AI document intelligence platform** that enables users to interact with private documents using natural language.

Unlike traditional chatbots that rely only on pre-trained knowledge, this application retrieves relevant information directly from uploaded documents before generating responses, providing accurate answers with document citations.

The system supports both **unstructured documents** (PDF, DOCX, PPTX) and **structured datasets** (CSV, Excel), making it useful for research, business analytics, education, and enterprise knowledge management.

---

# ✨ Features

## 📄 Document Intelligence

- Upload PDF, DOCX and PPTX files
- Semantic document search
- Multi-document querying
- Hybrid retrieval
- Source citations
- Page references
- Streaming AI responses

---

## 🔍 Advanced RAG Pipeline

- Retrieval-Augmented Generation
- Semantic Search
- Keyword Search
- Hybrid Ranking
- Cross-Encoder Re-ranking
- Context-aware chunking
- Persistent Vector Storage

---

## 📊 Spreadsheet Intelligence

Supports

- CSV
- XLSX

Capabilities

- Natural language queries
- Statistical summaries
- Table preview
- Data exploration
- Dynamic chart generation

---

## 🤖 Local Machine Learning

Train ML models directly on uploaded datasets.

Supported models

- Multiple Linear Regression
- Naive Bayes Classification
- K-Means Clustering

Includes

- MAE
- MSE
- R² Score
- Confusion Matrix
- Precision
- Recall
- F1 Score

---

## 🛡️ Secure Sandbox

Instead of allowing the LLM to guess spreadsheet calculations, the system generates JavaScript code and safely executes it inside a restricted VM Sandbox.

Features

- Isolated execution
- Timeout protection
- Restricted modules
- Safe local analysis

---

## 👤 Authentication

- User Registration
- Login
- JWT Authentication
- Password Hashing (bcrypt)
- User-specific document storage

---

## 🎯 AI Agent Studio

Create custom AI assistants by configuring

- System Prompt
- Temperature
- Agent Instructions

Each agent can specialize in different document tasks.

---

# 🏗️ Architecture

```
                User

                  │

                  ▼

          React + TypeScript UI

                  │

            Axios REST API

                  │

                  ▼

        Express.js Backend

      ┌─────────┼───────────┐

      ▼         ▼           ▼

 RAG Service  Sandbox     ML Service

      │         │           │

      ▼         ▼           ▼

 Vector DB   VM Runner   ML Models

      │

      ▼

 Gemini + Embeddings

      │

      ▼

   Source-Cited Answer
```

---

# 🧠 RAG Pipeline

```
Upload Document

       │

       ▼

Text Extraction

       │

       ▼

Chunking

       │

       ▼

Embeddings

       │

       ▼

Vector Storage

       │

       ▼

Hybrid Search

Semantic Search
      +
Keyword Search

       │

       ▼

Cross Encoder Reranking

       │

       ▼

Gemini LLM

       │

       ▼

Answer + Citations
```

---

# 🛠️ Tech Stack

## Frontend

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Radix UI
- Axios
- Recharts

---

## Backend

- Node.js
- Express.js
- Prisma ORM
- SQLite
- JWT Authentication
- Multer

---

## AI & NLP

- Google Gemini
- LangChain
- Gemini Embeddings
- MiniSearch
- HuggingFace Transformers
- Cross Encoder
- Server Sent Events (SSE)

---

## Machine Learning

- Multiple Linear Regression
- Naive Bayes
- K-Means

---

# 📂 Project Structure

```
RAG_Document_Assistant

│

├── RDA-frontend

│ ├── components

│ ├── api

│ ├── pages

│ └── App.tsx

│

├── backend

│ ├── prisma

│ ├── routes

│ ├── services

│ ├── middleware

│ ├── uploads

│ └── src

│

└── README.md
```

---

# ⚡ Installation

## Clone Repository

```bash
git clone https://github.com/Prathamesh-1705/RAG_Document_Assistant.git
```

```
cd RAG_Document_Assistant
```

---

## Backend

```
cd backend

npm install

npx prisma db push

npm run dev
```

---

## Frontend

```
cd RDA-frontend

npm install

npm run dev
```

---

## Open

```
http://localhost:5173
```

---

# 📷 Screenshots

> Add screenshots here

```
Home Page

Dashboard

Knowledge Base

Chat Interface

Sandbox

Agent Studio
```

---

# 🔥 Key Highlights

✅ Hybrid RAG

✅ Semantic Search

✅ Keyword Search

✅ Cross Encoder Re-ranking

✅ Multi-document Chat

✅ Spreadsheet Intelligence

✅ Local Machine Learning

✅ Secure Sandbox

✅ JWT Authentication

✅ Source Citations

✅ Streaming Responses

---

# 📈 Future Improvements

- OCR for scanned PDFs
- Audio document support
- Image understanding
- Voice interaction
- Multi-user collaboration
- PostgreSQL deployment
- Docker support
- Cloud deployment
- Llama 3 / Mistral support
- Conversation Memory

---

# 🎓 Learning Outcomes

This project demonstrates practical implementation of

- Retrieval-Augmented Generation (RAG)
- Large Language Models
- Vector Embeddings
- Semantic Search
- Full Stack Development
- Authentication
- Information Retrieval
- Machine Learning
- Secure Code Execution
- AI Application Development

---

# 👨‍💻 Author

**Prathamesh Tirmare**

AI & Data Science Engineer

GitHub:
https://github.com/Prathamesh-1705

---

## ⭐ If you found this project useful, don't forget to Star the repository!
