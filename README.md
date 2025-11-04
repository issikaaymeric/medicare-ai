# 🏥 MedicareAI

MedicareAI is an AI-powered assistant designed to help users ask questions, explore healthcare knowledge, and interact with intelligent models via a **React frontend** and a **FastAPI backend**.  
The project integrates Natural Language Processing (NLP) models to provide answers and insights in real time.

---

## 📌 Features
- 💬 **Chat Interface** – Ask health-related questions and get responses powered by AI.  
- ⚡ **FastAPI Backend** – Efficient Python backend for serving ML models.  
- 🎨 **React Frontend** – Clean user interface with sidebar navigation and chat input bar at the bottom.  
- 🤖 **Transformer-based AI Models** – Powered by Hugging Face `transformers`.  
- 🔒 **Secure Setup** – Environment variables used for API keys.  

---

## 🗂️ Project Structure
```

MedicareAI/
│── backend/         # FastAPI backend
│   ├── main.py      # API endpoints
│   ├── requirements.txt
│   └── ...
│
│── frontend/        # React frontend
│   ├── src/
│   ├── package.json
│   └── ...
│
│── README.md
└── .gitignore

````

---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAMe/MedicareAI.git
cd MedicareAI
````

### 2. Backend Setup

```bash
cd backend
python -m venv myenv
myenv\Scripts\activate  #If you're using Windows

pip install -r requirements.txt
```

Run the backend:

```bash
uvicorn main:app --reload --port 8000
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```
---

## 🚀 Usage

1. Start the backend (`uvicorn main:app --reload --port 8000`)
2. Run the frontend (`npm start`)
3. Open `http://localhost:3000` in your browser.
4. Ask MedicareAI questions like:

   * *“What is Medicare Part A?”*
   * *“Explain the eligibility criteria for Medicare.”*

---

## 🛠️ Tech Stack

* **Frontend:** React, React Icons
* **Backend:** FastAPI, Uvicorn, Transformers
* **AI Models:** OpenAI , Hugging Face Transformers (e.g., BERT, DistilBERT)
* **Deployment Ready:** GitHub + External storage for large files

---


## ✨ Acknowledgements

* [FastAPI](https://fastapi.tiangolo.com/)
* [React](https://react.dev/)
* [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)

---

## Documentations

### 1. **FastAPI + Hugging Face Inference API**

A clear and concise guide to creating FastAPI endpoints that serve LLM responses via Hugging Face’s Inference API—covers API key handling, endpoint setup, and error handling. ([deeplearningnerds.com](https://www.deeplearningnerds.com/build-a-llm-application-with-fastapi-and-hugging-face-inference-api/?utm_source=chatgpt.com))

### 2. **Building LLM Apps with FastAPI & Hugging Face Endpoints**

Step-by-step instructions for integrating Hugging Face endpoints with FastAPI. Great for understanding how to structure your inference service and expose it to your frontend. ([MachineLearningMastery.com](https://machinelearningmastery.com/building-llm-applications-with-hugging-face-endpoints-and-fastapi/?utm_source=chatgpt.com))

### 3. **FastAPI + React Full-Stack Deployment on Vercel**

Medium guide on combining Next.js (React) frontend and FastAPI backend, including deployment tips using Vercel. Helps with full-stack architecture and deployment workflows. ([Medium](https://medium.com/%40kaweyo_41978/boosting-your-full-stack-workflow-with-next-js-and-fastapi-and-vercel-3c7d3cd8220f?utm_source=chatgpt.com))

### 4. **Next.js AI App with Hugging Face Inference API**

A tutorial walking you through building a Next.js frontend integrated with Hugging Face Inference API—great for learning how to structure your UI and handle API interaction. ([Medium](https://medium.com/%40noorfatimaafzalbutt/building-a-next-js-ai-app-with-hugging-face-inference-api-dd93468d840e?utm_source=chatgpt.com))

### 5. **Secure AI App with FastAPI, LangChain & Hugging Face**

This tutorial adds another layer—JWT authentication and LangChain orchestration for LLMs—solid foundation for adding secure access and advanced prompt flows. ([djamware.com](https://www.djamware.com/post/6865fd6512ee9a10f92b095a/build-a-secure-ai-app-with-fastapi-langchain-and-hugging-face-transformers?utm_source=chatgpt.com))

### 6. **Hugging Face + FastAPI Minimal Starter**

A GitHub repo with a clean project structure demonstrating how to expose Hugging Face models via FastAPI, with Pydantic schemas, Docker, and tests. Perfect inspiration for your backend structure. ([GitHub](https://github.com/Proteusiq/huggingfastapi?utm_source=chatgpt.com))

### 7. **Deploy FastAPI via Docker to Hugging Face Spaces**

Explores how to containerize a FastAPI application and deploy it on Hugging Face Spaces—useful for sharing or portfolio hosting. ([Hugging Face](https://huggingface.co/blog/HemanthSai7/deploy-applications-on-huggingface-spaces?utm_source=chatgpt.com))

### 8. **Model Serving with FastAPI in 15 Minutes**

A fast and lightweight example of serving a Hugging Face transformer using FastAPI—great for quickly validating your backend inference logic. ([Medium](https://medium.com/%40hadiyolworld007/i-used-hugging-face-and-fastapi-to-serve-a-model-in-15-minutes-106caf998d1c?utm_source=chatgpt.com))

### 9. **Full Stack AI: RAG App with Next.js, FastAPI, Llama 3**

Learn about building Retrieval-Augmented Generation (RAG) apps using vector databases combined with Next.js and FastAPI—a great direction if you want to incorporate context retrieval and document indexing. ([Metadesign Solutions](https://metadesignsolutions.com/full-stack-ai-building-rag-apps-with-next-js-fastapi-and-llama-3-retrievalaugmented-generation-vector-dbs/?utm_source=chatgpt.com))

