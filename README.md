# Retrieval-Augmented Generation (RAG) System with Python & Ollama 🚀  

## Overview  
This repository contains a **Jupyter Notebook** that demonstrates how to build a **Retrieval-Augmented Generation (RAG) system** using:  
- **Python** 🐍  
- **Ollama** (for running LLM locally)  
- **LangChain** (for retrieval & orchestration)  
- **ChromaDB** (for vector storage)  
- **SentenceTransformers** (for text embeddings)  

### 🔹 What You'll Learn  
✅ What is RAG, and how does it work?  
✅ How to extract text from PDFs  
✅ How to create embeddings and store them in ChromaDB  
✅ How to retrieve relevant information  
✅ How to use Ollama’s LLM to generate responses  

---

## 📌 Installation  

1️⃣ **Clone this repository:**  
```bash
git clone https://github.com/yourusername/rag-system.git
cd rag-system
```

3️⃣ **Create a virtual environment & install dependencies:**
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install langchain chromadb sentence-transformers pypdf ollama
```
4️⃣ **Pull LLM Model:**
```bash
ollama pull llama3.2
```

## 🛠 Usage
### **Run the Jupyter Notebook (rag_system.ipynb) step-by-step to:**


✅ Load and process PDF documents  
✅ Generate text embeddings using SentenceTransformers  
✅ Store embeddings in ChromaDB for efficient retrieval  
✅ Query and retrieve relevant documents  
✅ Use Ollama’s LLM to generate responses  

