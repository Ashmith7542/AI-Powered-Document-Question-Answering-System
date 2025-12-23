🤖 AI-Powered Document Question Answering System

An AI-powered local Document Question Answering system that enables users to interact with PDF documents using Retrieval-Augmented Generation (RAG). The system processes documents locally using Ollama, LangChain, ChromaDB, and Streamlit, ensuring complete data privacy and offline operation.

📌 Project Overview

This project allows users to:

Upload PDF documents

Ask natural language questions

Retrieve accurate, context-aware answers from the document

It uses semantic search and large language models to eliminate the need for manually searching through lengthy documents.

🧠 System Architecture

The system follows a RAG (Retrieval-Augmented Generation) pipeline:

PDF text extraction

Text chunking

Embedding generation

Vector storage and retrieval

Context-aware answer generation using a local LLM

✨ Features

📄 Upload and process PDF documents

🔍 Semantic search using vector embeddings

🧠 Local LLM-based answer generation (Ollama)

🔒 Fully offline and privacy-preserving

🖥️ Interactive Streamlit web interface

⚡ Efficient handling of large documents

🛠️ Technologies Used

Python – Core programming language

LangChain – RAG pipeline orchestration

pdfplumber – PDF text extraction

Nomic-embed-text – Embedding generation

ChromaDB – Vector database

Ollama (Llama 3.2) – Local LLM inference

Streamlit – User interface

🚀 Installation & Setup
Prerequisites

Python 3.9 or above

Ollama installed locally

Step 1: Install Ollama Models
ollama pull llama3.2
ollama pull nomic-embed-text

Step 2: Clone the Repository
git clone https://github.com/Ashmith7542/AI-Powered-Document-Question-Answering-System.git
cd AI-Powered-Document-Question-Answering-System

Step 3: Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows

Step 4: Install Dependencies
pip install -r requirements.txt

▶️ Running the Application
streamlit run app.py


Then open:

http://localhost:8501

💡 How to Use

Upload a PDF document

Wait for indexing to complete

Enter a question related to the document

View the generated answer

📊 Performance & Reliability

Handles medium to large PDFs efficiently

Fast semantic retrieval using ChromaDB

Accurate responses with minimal hallucination

Stable performance on CPU-only systems

🔮 Future Enhancements

Multi-document support

Advanced summarization

Multilingual question answering

Integration with more advanced LLMs

Role-based user access

👨‍💻 Author

Ashmith Hamilpure
Komarraju Shivasai
Porandla Sreeja
Drona Madhuri Dadi
Final Year Academic Project
AI-Powered Document Question Answering System

✅ Following Steps

After pasting this into README.md:

git add README.md
git commit -m "Updated README with project description"
git push origin main