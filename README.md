# 🔎 LangChain - Chat with Search

This is a **Streamlit-based chatbot** powered by **LangChain** and **Groq's LLaMA 3** model.  
It can search the web, query Wikipedia, and retrieve research papers from Arxiv — all in real time.  

The app uses **LangChain Tools** and **Agents** to dynamically decide whether to search, look up Wikipedia, or fetch papers from Arxiv based on the user's query.  

---

## 🚀 Features
- **Real-time Web Search** using DuckDuckGo
- **Wikipedia Search** for quick factual lookups
- **Arxiv Research Paper Search** for academic queries
- **Conversational Agent** powered by `ChatGroq` with **LLaMA 3-8B**
- **Streaming Responses** with live token-by-token updates in Streamlit
- **Session Memory** to remember past chat messages
- **Interactive UI** with `StreamlitCallbackHandler` showing agent thoughts & actions

---

## 🛠 Tech Stack
- **Python 3.9+**
- **[LangChain](https://www.langchain.com/)**
- **[Groq API](https://groq.com/)**
- **[Streamlit](https://streamlit.io/)**
- **DuckDuckGo Search API**
- **Wikipedia API**
- **Arxiv API**
- **dotenv** for environment variable management

---

## 🖼 How It Works
1. Enter Groq API Key in the sidebar.
2. Type a question in the chat box.
3. The agent:
  - Decides whether to use DuckDuckGo, Wikipedia, or Arxiv.
  - Streams the answer back to you in real time.
4. All chat messages are stored in the session for context.

---

## ⚠ Notes
 - You must have a valid Groq API Key.
 - Internet access is required for DuckDuckGo, Wikipedia, and Arxiv queries.
 - Avoid committing .env to version control.

   
