# 🚀 Document-Drive: Full-Stack RAG Web App

![Status](https://img.shields.io/badge/Status-Completed-success)
![React](https://img.shields.io/badge/Frontend-React.js-blue)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-teal)
![AI](https://img.shields.io/badge/AI-LangChain%20%7C%20OpenAI-purple)

**Document-Drive** is a smart search platform that uses Retrieval-Augmented Generation (RAG) to instantly answer questions based on your uploaded documents. 

I built this project to demonstrate how to combine a modern React frontend and a fast Python backend with Large Language Models (LLMs) to create powerful, AI-driven applications.

---

## 💡 What I Learned / Skills Demonstrated
- **Frontend Development**: Building a responsive, interactive UI using React.js.
- **Backend API Engineering**: Developing fast, asynchronous APIs using Python and FastAPI.
- **AI / Machine Learning Integration**: Implementing RAG pipelines using Langchain, OpenAI models, and Vector Databases.
- **Data Management**: Utilizing ChromaDB for vector storage and semantic search, and AWS S3 for document storage.
- **Problem Solving**: Orchestrating different microservices and connecting the frontend and backend efficiently.

## 🛠️ Technology Stack
- **Frontend**: React.js, HTML, CSS
- **Backend API**: Python, FastAPI
- **AI Framework**: Langchain
- **LLM Provider**: OpenAI
- **Vector Database**: ChromaDB
- **Cloud/Storage**: AWS S3 (boto3)

---

## 🚀 How to Run Locally

If you want to test out my project on your own machine, follow these simple steps!

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/RAGv1-Full-Stack.git
cd RAGv1-Full-Stack
```

### 2. Frontend Setup
```bash
cd frontend
npm install
npm start
```
*The React app will be running at `http://localhost:3000`*

### 3. Backend Setup
Create your `.env` file with your `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, `AWS_REGION`, `AWS_S3_BUCKET_NAME`, and `OPENAI_API_KEY`.
```bash
cd backend
# Install dependencies
pip install fastapi uvicorn boto3 python-dotenv pydantic langchain-community chromadb openai pypdf langchain-text-splitters
# Start the server
python main.py
```
*The FastAPI server will be available at `http://localhost:8000`*

---

> Built with passion to explore the power of AI in web development! 💻
