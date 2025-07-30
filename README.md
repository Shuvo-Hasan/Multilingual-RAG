# RAG Pipeline – Work in Progress 🚧

This is a **Research & Development** project for building a **Retrieval-Augmented Generation (RAG)** pipeline using `sentence-transformers`, `ChromaDB`, and optionally `LangChain`.  
It’s currently a **work in progress** and not fully functional yet.

---

## 📌 Goal

To create a multilingual RAG pipeline that:
- Extracts and chunks documents
- Embeds text using transformer-based models (e.g., LaBSE)
- Stores and retrieves embeddings using a vector store (ChromaDB)
- Generates answers to user queries based on relevant retrieved chunks

---

## ✅ Current Progress

- [x] Document cleaning (Unicode normalization, punctuation cleanup, etc.)
- [x] Text chunking
- [x] Embedding generation using `sentence-transformers`
- [x] Storing embeddings in ChromaDB
- [ ] Connecting with a language model to generate answers
- [ ] Building a basic user interface or API

---

## 🚧 Next Steps

- [ ] Integrate a language model for answer generation (OpenAI / LLaMA / Ollama, etc.)
- [ ] Improve chunking logic for multilingual text
- [ ] Add query interface (CLI or web)
- [ ] Add unit tests for key components
- [ ] Refactor into modular, testable components

---

## 🛠️ Tech Stack

- Python 3.10+
- [`sentence-transformers`](https://www.sbert.net/)
- [`ChromaDB`](https://www.trychroma.com/)
- `faiss` or `chromadb` as vector store
- (Planned) `LangChain`, `FastAPI`, or `Gradio`

---

## 📂 Structure
