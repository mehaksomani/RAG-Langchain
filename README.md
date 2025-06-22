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

## Project Structure

