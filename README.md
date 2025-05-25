# 🧠 MediBot: AI Medical Chatbot with RAG (LangChain + Hugging Face + Streamlit)

MediBot is a domain-specific **Retrieval-Augmented Generation (RAG)** chatbot designed to answer medical questions using verified health resources like the **Gale Encyclopedia of Medicine**. It uses semantic document search combined with large language models to generate accurate and trustworthy responses.

## 🚀 Features
- 🔍 Semantic PDF Retrieval with FAISS
- 🧠 Medical Q&A with Hugging Face LLMs (e.g., Mistral 7B)
- 📄 Load and chunk medical documents (PDF support)
- 🌐 User-friendly Streamlit Chat UI
- 🔐 `.env` support for secure Hugging Face token usage
- 🧪 Ideal for private healthcare knowledge base chatbots

## 🧰 Tech Stack
| Component              | Description                                         |
|------------------------|-----------------------------------------------------|
| 🤗 Hugging Face         | LLM inference (e.g., Mistral 7B via API)           |
| 🔗 LangChain            | Document pipeline + QA orchestration               |
| 🔍 FAISS                | Fast vector similarity search                      |
| 🧬 SentenceTransformers | Embedding generation (`all-MiniLM-L6-v2`)         |
| 📄 PyMuPDF              | PDF parsing and chunking                          |
| 📺 Streamlit            | Frontend web UI for chatting with the bot         |


## 🔧 Running the App
     Streamlit Web Ui
## 📌 Requirments
    langchain
    langchain_community
    langchain_huggingface
    faiss-cpu
    pypdf
    huggingface_hub
    streamlit

## 🧑‍💻 Author
**Saad Saddique**  
AI/ML Developer | NLP Enthusiast

## 📜 License
MIT License
