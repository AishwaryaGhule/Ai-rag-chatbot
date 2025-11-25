# Medical RAG Chatbot – NAFLD (Non-Alcoholic Fatty Liver Disease)

A Retrieval-Augmented Generation (RAG) based medical chatbot that answers questions related to **Non-Alcoholic Fatty Liver Disease (NAFLD/NASH)** using reference documents such as articles, guidelines and notes.  
This project is for **educational and research demonstration only**, not medical advice.

---

## 🔍 What This Project Does
- Loads medical PDFs/Text documents related to NAFLD
- Splits content into small chunks for retrieval
- Converts text to embeddings using LLM embeddings
- Stores embeddings in a FAISS vector database
- Retrieves relevant context for user questions
- Generates **accurate, context-aware answers** using an LLM

---

##  Tech Stack
| Area              | Tools Used        |
|-------------------|-------------------|
| Language Model    | OpenAI / LLM      |
| Framework         | LangChain         |
| Vector Database   | FAISS             |
| Document Handling | PyPDF, TextLoader |
| Programming       | Python            |
| Notebook          | Jupyter Notebook  |

---

## 🗂 Project Structure
