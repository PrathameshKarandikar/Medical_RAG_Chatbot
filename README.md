# 🏥 Medical RAG Chatbot

This project implements a **Retrieval-Augmented Generation (RAG) Chatbot** for answering medical-related queries.  
It combines **LangChain**, **HuggingFace Embeddings**, **ChromaDB**, and a **HuggingFace Chat Model** to provide accurate, context-aware answers.  
A **Gradio** interface is used for easy interaction.  

---

## 🚀 Features
- ✅ Retrieval-Augmented Generation (RAG) pipeline for contextual answers  
- ✅ Uses **HuggingFace Sentence Transformers** for embeddings  
- ✅ Stores and retrieves knowledge from **ChromaDB**  
- ✅ HuggingFace Chat Model for natural responses  
- ✅ **Gradio Demo UI** for user interaction  

---

## 🛠️ Tech Stack
- **LangChain** – RAG orchestration  
- **HuggingFace Sentence Transformers** – Embeddings (`all-MiniLM-L6-v2`)  
- **ChromaDB** – Vector database for storage and retrieval  
- **HuggingFace Chat Model** – LLM for generating responses  
- **Gradio** – Web-based demo interface  

---

## 📂 Project Structure

medical-rag-chatbot/

│── data/

│ └── medical_qna.csv # Medical Q&A dataset

│── medical_RAG_chatbot.ipynb # Main Notebook with RAG pipeline + Gradio demo

│── README.md # Project documentation

## 🔧 How It Works

1. Load Dataset → Import medical Q&A data.

2. Embed Documents → Convert text into embeddings using HuggingFace Sentence Transformer.

3. Store in ChromaDB → Save embeddings in a vector database.

4. RAG Pipeline → Retrieve relevant chunks and generate answers using HuggingFace Chat Model.

5. Gradio UI → User inputs query, chatbot returns contextual answer.
