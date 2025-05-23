RAG Document Q&A with Groq and Llama3
This project is a Retrieval-Augmented Generation (RAG) based chatbot built using Streamlit and LangChain. It allows you to ask questions based on a collection of research papers in PDF format, and receive accurate, context-aware answers powered by Groq's Llama3 model and OpenAI embeddings.

Features
Ingest multiple PDF research papers for document understanding

Split documents into manageable text chunks for better retrieval

Create vector embeddings using OpenAI embeddings

Store embeddings efficiently with FAISS vector store

Retrieve relevant document chunks dynamically for question answering

Use Groq's Llama3 large language model to generate precise answers

Interactive Streamlit UI for easy querying and visualization of retrieved docs

Installation & Setup
Clone the repository

Create and activate a Python virtual environment

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file and add your API keys:

env
Copy
Edit
OPENAI_API_KEY=your_openai_api_key_here
GROQ_API_KEY=your_groq_api_key_here
Place your PDF research papers inside the research_papers folder

Usage
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Click Document Embedding to process and index your PDFs

Enter a query in the text box and get accurate answers based on the loaded documents

Expand the "Document similarity Search" section to view the relevant source documents

Technologies Used
Streamlit for the user interface

LangChain for chaining LLMs with document retrieval

Groq Llama3 large language model for answering questions

OpenAI Embeddings for vectorizing text

FAISS for efficient similarity search

PDF document loading and splitting utilities for text preprocessing

Notes
Make sure your API keys are valid and have necessary permissions

The document loader currently processes up to 50 documents for performance

Chunk size and overlap can be adjusted for better context handling

Response time depends on model and query complexity

