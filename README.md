

📄 Information Retrieval from Multiple PDFs using Google GenAI

A conversational RAG system that allows users to upload multiple PDF files and ask questions about their content.
Built with LangChain, FAISS, Google GenAI, and Streamlit.

🚀 Features

📤 Upload multiple PDF files

📚 Extract and preprocess text

🔍 Split text into meaningful chunks for high-quality retrieval

🧠 Generate vector embeddings with Google GenAI

⚡ Store and search embeddings using FAISS

💬 Conversational multi-turn Q&A using a RAG pipeline

🌐 Clean and interactive Streamlit UI

🛠️ Tech Stack
Component	Purpose
Python	Core programming language
Streamlit	Web interface for chat and file uploads
LangChain	Text splitting, embeddings, and RAG pipeline
Google GenAI API	Embeddings + LLM for responses
FAISS	Vector database for fast semantic search
🏗️ How to Run the Project

Follow these steps to get the project running locally:

1️⃣ Clone the repository
git clone https://github.com/your-repo-name
cd your-repo-name

2️⃣ Create and activate a Conda environment
conda create -n llmapp python=3.8 -y
conda activate llmapp

3️⃣ Install required dependencies
pip install -r requirements.txt

4️⃣ Add your environment variables

Create a .env file in the project root and add:

GOOGLE_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxx

5️⃣ Run the Streamlit app
streamlit run app.py

6️⃣ Open in browser

Visit:

http://localhost:8501

📦 Project Workflow

Upload PDFs

Extract raw text

Split text into smaller chunks

Create embeddings using Google GenAI

Store vectors in FAISS

Semantic search + conversational querying

LLM generates human-like answers with retrieved context
