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

# 🔑 Environment Variables

Create a `.env` file inside the `backend` folder and add the following:

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
JWT_SECRET=YOUR_SECRET_KEY
```

Replace `YOUR_GEMINI_API_KEY` with your own Google Gemini API key before running the application.

# ⚙️ How to Run the Project

## Prerequisites

Make sure you have installed:

- Node.js (v18 or later)
- npm
- Git
- A Google Gemini API Key

---

## Step 1: Clone the Repository

```bash
git clone https://github.com/Prathamesh-1705/RAG_Document_Assistant.git
```

```bash
cd RAG_Document_Assistant
```

---

## Step 2: Open the Project

Open the **RAG_Document_Assistant** folder in **Visual Studio Code** (or any IDE of your choice).

---

## Step 3: Start the Backend Server

Open the **first terminal** inside VS Code.

Navigate to the backend folder:

```bash
cd backend
```

Install dependencies (first time only):

```bash
npm install
```

Create the SQLite database using Prisma:

```bash
npx prisma db push
```

Now start the backend server:

```bash
npm run dev
```

The backend server will start successfully.

---

## Step 4: Start the Frontend

Open a **second terminal**.

Navigate to the frontend folder:

```bash
cd RDA-frontend
```

Install dependencies (first time only):

```bash
npm install
```

Start the React application:

```bash
npm run dev
```

---

## Step 5: Open the Application

After the frontend starts, Vite will display a local URL similar to:

```text
http://localhost:5173
```

Open this link in your browser.

🎉 Your **RAG Document Assistant** is now ready to use!

You can now:

- 📄 Upload PDF, DOCX, PPTX, CSV, or Excel files
- 💬 Chat with your documents
- 🔍 Perform Semantic & Hybrid Search
- 📊 Analyze spreadsheets
- 🤖 Train Machine Learning models
- 🧠 Create custom AI agents
- 📑 View source citations for every response

