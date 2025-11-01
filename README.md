# Medical-Chatbot


## 🚀 Project Overview  
The Medical-Chatbot is a context-aware AI assistant that uses Retrieval-Augmented Generation (RAG) techniques to answer medical queries accurately and intelligently. Leveraging large-language models, semantic search (via FAISS) and LangChain, it provides relevant, coherent responses to user inputs using a curated medical dataset.

## 🧠 Key Features  
- Semantic retrieval: uses FAISS vector embeddings to match user queries with relevant medical documents.  
- RAG pipeline: integrates LangChain with a base LLM for generation of medically-framed responses.  
- Easy deployment: containerised (Docker) and ready for cloud or on-premise usage.  
- Modular architecture: clean separation between data ingest, index build, and query interface.  
- Secure & responsible: designed for educational and consultation contexts (not a substitute for professional medical advice).

## 🛠️ Tech Stack  
- Python (for backend logic)  
- LangChain (for RAG orchestration)  
- FAISS (for vector similarity search)  
- Flask / FastAPI (for web interface or API endpoints)  
- GitHub (version control & collaboration)

## 🧪 Example Usage  
1. Clone the repository  
   ```bash
   git clone https://github.com/SRINU102/Medical-Chatbot.git
