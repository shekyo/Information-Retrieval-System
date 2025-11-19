# Information Retrieval from Multiple PDFs 💁💬 with Google GenAI

A **conversational AI system** that allows users to upload multiple PDF files and ask questions about their content. This project demonstrates **RAG (Retrieval-Augmented Generation)** using **LangChain**, **FAISS**, and **Google GenAI API**.

---

## How to Run

### Steps:

1. **Clone the repository**  
```bash
git clone https://github.com/your-repo-name
cd your-repo-name
Create and activate a conda environment

bash
Copy code
conda create -n llmapp python=3.8 -y
conda activate llmapp
Install the required packages

bash
Copy code
pip install -r requirements.txt
Set up environment variables

Create a .env file in the root directory

Add your Google GenAI API key:

ini
Copy code
GOOGLE_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Run the Streamlit app

bash
Copy code
streamlit run app.py
Open in browser

Visit: http://localhost:8501

Tech Stack
Python – core programming language

Streamlit – for web interface and interactivity

LangChain – for text splitting, embeddings, and RAG

Google GenAI API – for embeddings and language model generation

FAISS – vector database for semantic search

Project Features
Upload multiple PDF files and extract text

Split text into manageable chunks for better retrieval

Generate vector embeddings using Google GenAI

Store embeddings in FAISS for fast semantic search

Build a conversational retrieval chain for multi-turn question-answering

Streamlit interface for interactive queries
