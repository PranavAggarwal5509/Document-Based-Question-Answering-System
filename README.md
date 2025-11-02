# Document-Based-Question-Answering-Chatbot (Offline RAG System)

A fully **offline chatbot** that can read any **PDF or text document** and answer user questions using **Retrieval-Augmented Generation (RAG)** — without any external API keys or internet connection.

---

## 🚀 Features
- Accepts any local `.pdf` or `.txt` document.
- Uses **FAISS** for fast similarity-based search.
- Uses **Sentence Transformers** for embeddings.
- Uses **FLAN-T5** for local answer generation.
- Runs completely **offline** (no API dependency).

---

## 🧠 Tech Stack
- **Python 3.10+**
- **FAISS** – similarity search engine  
- **Sentence Transformers** – for document embeddings  
- **Transformers (Flan-T5)** – for local answer generation  
- **PyMuPDF / PDFMiner** – PDF text extraction  
- **Streamlit (optional)** – for UI interface  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/Document-QA-Chatbot.git
cd Document-QA-Chatbot

pip install -r requirements.txt
