# 🔍 Non-RAG RAG Pipeline for Coding Copilot  
*A Retrieval-Augmented Generation Architecture for Code Intelligence*  
**By Khushi Malik**

---

## 📘 Overview

This project demonstrates a functional **RAG (Retrieval-Augmented Generation) pipeline** tailored for **code comprehension and assistance**, using the Flask codebase as a domain-specific example. Built entirely in **Google Colab**, this implementation integrates:

- 🧠 **Code Embeddings** with `BAAI/bge-code-v1`  
- 💬 **LLM Tokenization & Generation** via `bigcode/starcoder2-3b`  
- 🧩 **Semantic Retrieval** using `ChromaDB`  
- ⚙️ **Power Prompting** for improved response accuracy

The pipeline enables **Large Language Models** to respond with enhanced accuracy and context-awareness when dealing with real-world codebases—minimizing hallucinations and increasing relevance.

---

## 🚀 Features

- ✅ Automatic ingestion of Python code from a real GitHub codebase (Flask)  
- ✅ Code chunking via `LangChain` with overlap control  
- ✅ Code embedding using HuggingFace SentenceTransformer  
- ✅ Vector storage and semantic retrieval via ChromaDB  
- ✅ Power Prompt generation for code explanation or Q&A  
- ✅ End-to-end runnable inside Google Colab  

---

## 📂 Project Structure
├── RAG_pipeline.ipynb # Full implementation in Google Colab
├── README.md # This file
└── assets/ # (Optional) Diagrams, screenshots

---

## 🛠️ Technologies Used

| Component        | Tool/Model                     |
|------------------|--------------------------------|
| Embeddings       | `BAAI/bge-code-v1`             |
| Tokenizer/LLM    | `bigcode/starcoder2-3b`        |
| Vector Store     | `ChromaDB`                     |
| Chunking/Tools   | `LangChain`, `SentenceTransformers` |
| Environment      | Google Colab                   |

---

## 📈 How It Works

1. **Clone Flask Codebase**
   ```python
   !git clone https://github.com/pallets/flask /content/sample_codebase

---

## 🧪 Run It Yourself

▶️ **Google Colab Notebook**:  
[📓 Click to Open](https://colab.research.google.com/drive/10iI32qEqV1jIMZBXZw_PnzVnITgn7IM3#scrollTo=8koZennMSgfU)

---

## 🔮 Future Enhancements

- 🌲 AST-based chunking (preserve function/class boundaries)  
- 🔌 LLM API integration (OpenAI, Gemini, HuggingFace Inference)  
- 🖥️ Web-based UI using Gradio or Streamlit  
- 💾 Persistent vector store (LanceDB, Pinecone, Weaviate)  
- 📊 Retrieval + generation evaluation metrics  
- 🔁 Re-ranking using cross-encoders or hybrid retrieval  

---

## 📄 Related Resources

- 📄 [Full Project Report](https://docs.google.com/document/d/1KGo6q_H9NBX_aP2eNpYPWZpQYCZqVoeLg5MwL4UEvh0/edit)  
- 📘 [RAG Architecture Overview](https://docs.google.com/document/d/1V7L6gJCzp8Nu_x0Xt_i1gJXQKf0riz86fLsYwdwOYO8/edit?usp=sharing)  
- ✍️ [Medium Article](https://medium.com/@khushimalik511263/building-a-rag-pipeline-for-a-coding-copilot-df3e6fce257e)

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
Please open issues for bugs, improvements, or feature discussions.

---

## 👩‍💻 Author

**Khushi Malik**  
AI Researcher | Developer Tools Innovator | LLM Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/khushi-6b972b280/) 
📧 khushimalik511263@gmail.com 

---

Feel free to use, fork, and contribute with credit.

---

