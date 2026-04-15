# 🚀 AI Document Q&A (RAG Chatbot)

## 📌 Status

🚧 Currently in development

---

## 📖 Overview

This project is an AI-powered chatbot that allows users to upload documents (PDFs) and ask questions based on their content. It uses **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware answers.

---

## 🧠 Features

* 📂 Upload PDF documents
* 💬 Ask questions from documents
* 🧠 Context-aware answers using LLM
* 🔎 Semantic search using vector database
* 📄 Source-based responses

---

## 🛠 Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* FastAPI (Python)

### AI / ML

* Embeddings (Sentence Transformers)
* FAISS (Vector Database)
* LLM (OpenAI / Local Model)

---

## ⚙️ How It Works

1. Upload PDF
2. Extract text from document
3. Split text into chunks
4. Convert chunks into embeddings
5. Store embeddings in vector database
6. User asks a question
7. Relevant chunks are retrieved
8. LLM generates final answer

---

## 📁 Project Structure

```
ai-document-qa-rag/
│── client/        # React frontend
│── server/        # FastAPI backend
│── README.md
│── requirements.txt
```

---

## 🚀 Run Locally

### Backend (FastAPI)

```bash
cd server
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend (React)

```bash
cd client
npm install
npm start
```

---

## 📅 Development Roadmap

* [ ] Backend setup
* [ ] PDF text extraction
* [ ] Chunking logic
* [ ] FAISS integration
* [ ] RAG pipeline
* [ ] Chat API
* [ ] Frontend UI
* [ ] Deployment

---

## 📸 Screenshots

(Add screenshots here after UI is ready)

---

## 🌐 Live Demo

(Add deployed link here)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## 📌 Author

**Ritik Gupta**
💼 Full Stack Developer | AI Enthusiast

---

⭐ If you like this project, give it a star!
