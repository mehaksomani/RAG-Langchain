# RAG LangChain AI Assistant

An end-to-end Retrieval-Augmented Generation (RAG) application built using **LangChain**, **Streamlit**, **LLMs**, and **Vector Databases**.  
This project demonstrates how to build a fully functional AI assistant that can understand queries and respond with context-aware answers from custom data sources.

## Features

- **User Upload**: Upload documents for knowledge base creation  
- **Semantic Search**: Retrieve relevant chunks using vector similarity  
- **LLM Integration**: Use top models (OpenAI, Ollama, etc.) for contextual answers  
- **Streamlit UI**: Clean, interactive interface to upload, query, and review answers  
- **Multi-LLM Comparison (Optional)**: Compare outputs from 2-3 different LLMs  
- **Modular Design**: Easily swap out LLMs or vector stores (FAISS, Chroma, etc.)  

## Tech Stack

<table>
  <thead>
    <tr><th>Technology</th><th>Description</th></tr>
  </thead>
  <tbody>
    <tr><td>Python</td><td>Backend and ML pipelines</td></tr>
    <tr><td>LangChain</td><td>RAG orchestration and chain logic</td></tr>
    <tr><td>Streamlit</td><td>Frontend web interface</td></tr>
    <tr><td>FAISS / Chroma</td><td>Vector database for document retrieval</td></tr>
    <tr><td>Ollama / OpenAI</td><td>LLMs for answer generation</td></tr>
    <tr><td>BeautifulSoup</td><td>Web document scraping (if enabled)</td></tr>
  </tbody>
</table>

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/rag-langchain.git
cd rag-langchain
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Environment Variables

Create a `.env` file or export directly:

```
OPENAI_API_KEY=your_openai_key
```

### 5. Run the App

```bash
streamlit run apps/web_rag.py
```

## Deployment

This app can be deployed on:

- Streamlit Cloud  
- Render / Railway / Hugging Face Spaces  

Ensure your vector database and LLMs are properly configured for deployment environments.

## Learning Resources

- [LangChain Documentation](https://docs.langchain.com)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [RAG Blog Post](https://www.riis.com/blog/introduction-to-rag-with-langchain-and-openai)
- [Ollama Setup](https://ollama.com/)
- [YouTube RAG Tutorial](https://youtu.be/YLPNA1j7kmQ?si=jV2yH3ltUaiq434a)

Thankyou for watching!
