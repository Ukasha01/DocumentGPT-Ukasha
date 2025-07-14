# 📚 Document GPT — AI Chatbot for Your Documents

> 🚀 Built by Muhammad Ukasha Ghufran  
> 🤖 Powered by Google Gemini + LlamaIndex + ChromaDB  
> 🧠 Understand any document instantly with AI

---

## 🔍 What is Document GPT?

**Document GPT** is a smart, conversational AI chatbot that lets you:

- 📄 Upload documents (PDF, DOCX, TXT)
- 💬 Ask questions in natural language
- 🤖 Get context-aware answers — powered by Google Gemini
- 🧠 Uses **ChromaDB** to store and recall document embeddings
- 🧠 Embeddings via HuggingFace Transformers (`MiniLM`)

It’s like having your own **personal research assistant** for any file you upload!

---

## 🎯 Why This Project Matters

✅ Practical Use Case  
✅ Free + Open Source  
✅ Deployable Anywhere  
✅ Powered by LLMs & Vector Databases  
✅ Real-time Document QA Chatbot  
✅ Recruiters Love Real Projects — This is it!

---

## 💡 Features

- ✔️ Upload multiple file types (PDF, DOCX, TXT)
- ✔️ Automatic document vectorization using HuggingFace embeddings
- ✔️ Persistent vector memory via ChromaDB
- ✔️ Query using **Google Gemini**
- ✔️ Clean Gradio Chat UI
- ✔️ Friendly and polite AI assistant

---

## 🛠️ Tech Stack

| Layer       | Tool / Library |
|-------------|----------------|
| 💬 LLM       | Google Gemini (via `llama-index-llms-gemini`) |
| 🧠 Embeddings| HuggingFace MiniLM (`sentence-transformers`) |
| 📦 Vector DB | ChromaDB (local persistent storage) |
| 🧱 Framework | LlamaIndex (for index + query logic) |
| 🌐 Frontend  | Gradio UI |

---

## 🚀 How It Works

1. Upload any document
2. The bot reads and stores it as embeddings in ChromaDB
3. You ask a question
4. Query runs through Gemini with context
5. Response is shown in chat

---

## 📁 File Structure

