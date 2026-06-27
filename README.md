# 📚 Multi-PDF Chatbot

> **An AI-powered conversational document assistant that enables users to chat with multiple PDF documents, retrieve accurate answers, and enhance information discovery using Retrieval-Augmented Generation (RAG).**

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![LangChain](https://img.shields.io/badge/LangChain-LLM%20Framework-green)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Database-orange)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue?logo=google)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Project Overview

Multi-PDF Chatbot is an **AI-powered Retrieval-Augmented Generation (RAG)** application that allows users to upload multiple PDF documents and interact with them through natural language conversations. The chatbot retrieves relevant information using vector search and generates context-aware responses with Google's Gemini model.

The project improves document search, knowledge retrieval, and information discovery by combining **LangChain**, **FAISS**, and **Gemini** into an intelligent conversational assistant.

---

# 🎯 Objectives

- 📄 Upload and process multiple PDF documents
- 💬 Ask questions in natural language
- 🔍 Retrieve the most relevant document content
- 🤖 Generate context-aware responses using Gemini
- ⚡ Improve information discovery from large document collections

---

# ✨ Features

- Multi-PDF document upload
- Conversational AI interface
- Retrieval-Augmented Generation (RAG)
- Semantic document search
- Context-aware question answering
- Fast vector similarity search using FAISS
- Interactive Streamlit web application
- Supports multiple user queries in a conversation

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| LLM Framework | LangChain |
| Vector Database | FAISS |
| Large Language Model | Google Gemini |
| Web Framework | Streamlit |
| Embeddings | Gemini Embeddings / Google AI Embeddings |

---

# 📂 Project Structure

```
Multi-PDF-Chatbot/
│
├── data/
├── documents/
├── embeddings/
├── vector_store/
├── src/
│   ├── pdf_loader.py
│   ├── text_splitter.py
│   ├── embeddings.py
│   ├── vectorstore.py
│   ├── chatbot.py
│   └── app.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ Workflow

```
Upload PDFs
      │
      ▼
Extract Text
      │
      ▼
Split into Chunks
      │
      ▼
Generate Embeddings
      │
      ▼
Store in FAISS
      │
      ▼
User Question
      │
      ▼
Similarity Search
      │
      ▼
Retrieve Context
      │
      ▼
Gemini Response
```

---

# 🧠 RAG Pipeline

- Upload one or more PDF files
- Extract text from documents
- Split text into manageable chunks
- Generate embeddings
- Store embeddings in FAISS vector database
- Receive user query
- Retrieve the most relevant chunks
- Generate an accurate answer using Gemini
- Display the response in Streamlit

---

# 📊 Expected Output

- Conversational interface
- Context-aware answers
- Relevant document references
- Fast semantic search
- Multi-document question answering
- Improved document accessibility

---

# 🚀 Applications

- Enterprise Knowledge Base
- Research Paper Assistant
- Legal Document Analysis
- Educational Learning Assistant
- HR Policy Chatbot
- Healthcare Documentation
- Financial Report Analysis
- Internal Company Documentation

---

# 📈 Future Enhancements

- Support for DOCX, TXT, and PPT files
- Chat history persistence
- User authentication
- Citation and source highlighting
- Voice-based interaction
- Multi-language document support
- Cloud deployment
- Integration with multiple LLM providers

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Multi-PDF-Chatbot.git
```

Navigate to the project folder

```bash
cd Multi-PDF-Chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

# 📦 Requirements

- Python 3.10+
- LangChain
- FAISS
- Streamlit
- Google Generative AI SDK
- PyPDF2

Install manually

```bash
pip install langchain faiss-cpu streamlit google-generativeai PyPDF2
```

---

# 📸 Demo

> Add screenshots or GIFs showing:
>
> - PDF upload interface
> - Chat interface
> - Question answering
> - Document retrieval process
> - Generated responses

---

# 📚 Learning Outcomes

This project demonstrates practical implementation of:

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- LangChain Framework
- Vector Databases (FAISS)
- Semantic Search
- Embeddings
- Conversational AI
- Prompt Engineering

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👩‍💻 Author

**Renuka Khopale**

AI Engineer • Generative AI • LangChain • LLMs • RAG • NLP

⭐ If you found this project useful, don't forget to **Star** the repository!
