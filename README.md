# 📄 Information Retrieval from Multiple PDFs using Google GenAI

A conversational **RAG (Retrieval-Augmented Generation)** system that allows users to upload multiple PDF files and ask questions about their content.  
Built with **LangChain, FAISS, Google GenAI, and Streamlit**.

## 🚀 Features

- 📤 Upload multiple PDF files  
- 📚 Extract and preprocess text  
- 🔍 Split text into meaningful chunks for high-quality retrieval  
- 🧠 Generate vector embeddings using Google GenAI  
- ⚡ Store and search embeddings using FAISS  
- 💬 Conversational multi-turn Q&A with a full RAG pipeline  
- 🌐 Clean and interactive Streamlit UI  

## 🛠️ Tech Stack

| Component           | Purpose                                  |
|--------------------|-------------------------------------------|
| Python             | Core programming language                 |
| Streamlit          | Web interface for chat + file uploads     |
| LangChain          | Text splitting, embeddings, RAG pipeline  |
| Google GenAI API   | LLM + embeddings generation               |
| FAISS              | Vector database for fast retrieval        |

## 🏗️ How to Run the Project

Follow these steps to run the project locally:

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Information-Retrieval-System

cd Information-Retrieval-System

```

### 2️⃣ Create and activate a Conda environment
```bash
conda create -n llmapp python=3.8 -y
conda activate llmapp
```

### 3️⃣ Install required dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Add your environment variables

Create a `.env` file in the project root:

```
GOOGLE_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

### 5️⃣ Run the Streamlit app
```bash
streamlit run app.py
```

### 6️⃣ Open in browser

Visit:  
http://localhost:8501

## 📦 Project Workflow

1. Upload PDFs  
2. Extract raw text  
3. Split text into smaller chunks  
4. Generate embeddings using Google GenAI  
5. Store vectors in FAISS  
6. Perform semantic search + conversational querying  
7. LLM generates human-like answers with retrieved context  
