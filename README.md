# 🎥 YouTube Chatbot with Streamlit + Gemini Embeddings

This project is a **Streamlit-based chatbot** that lets you ask questions about any YouTube video.  
It uses:
- **YouTube Transcript API** to fetch captions  
- **Gemini (`models/embedding-001`)** for free embeddings  
- **FAISS** for vector search  
- **LangChain + Gemini LLM** for conversational responses  

---

## 🚀 Features
- Extracts YouTube video transcripts automatically  
- Splits transcripts into chunks for retrieval  
- Uses **Gemini embeddings** (free tier available)  
- Answers questions based only on the transcript content  
- Simple Streamlit interface  
- Deployable on **Render** for free hosting  

---

## 🛠️ Installation (Local)
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/youtube-chatbot.git
   cd youtube-chatbot
