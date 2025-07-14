# 📚 Document GPT – AI Chatbot for Your Documents

**Developed by Muhammad Ukasha Ghufran**

This AI-powered chatbot can read documents (PDF, DOCX, TXT) and answer questions based on their content.  
It uses:

- 🧠 **Google Gemini Pro** – for answering and main brain
- 📦 **LlamaIndex** – for document parsing and all framework
- 🧬 **HuggingFace Embeddings**
- 💾 **ChromaDB** – for vector embedding storage 
- 🌐 **Gradio** – web-based chat interface

---

## 🚀 How It Works

1. Upload any document
2. It extracts & stores its text using embeddings
3. Ask any question – it answers using LLM based on only that document

---

## 🛠️ Technologies

| Feature       | Tool Used                      |
|---------------|--------------------------------|
| Embedding     | `sentence-transformers/all-MiniLM-L6-v2` |
| Vector DB     | `ChromaDB`                     |
| LLM           | `Google Gemini 1.5 Flash`      |
| Interface     | `Gradio`                       |
| Framework     | `LlamaIndex`                   |

---

## 🔐 Environment Variables

To run it, set this in your environment:

GEMINI_API_KEY = your_api_key_here

# 🧪 Demo

Live version deployed on Hugging Face:  
🔗 [Click to Chat with Document GPT]([(https://huggingface.co/spaces/muhammadukasha/Ukasha_DocumentGPT))

> Built with ❤️ by Ukasha – passionate about AI, Chatbots & Innovation!


