RAG Document Q&A with Groq and Llama3
This project is an interactive Streamlit application that enables question-answering over a collection of research papers using advanced AI models and retrieval-augmented generation (RAG). It leverages Groq’s Llama3 model along with OpenAI embeddings and FAISS vector search to provide accurate answers grounded in the source documents.

Key Features
Document Ingestion & Splitting: Automatically loads and processes PDF research papers, splitting them into manageable text chunks for efficient retrieval.

Vector Embeddings: Converts text chunks into vector embeddings using OpenAI’s embedding models, enabling semantic similarity search.

Retrieval-Augmented Generation (RAG): Retrieves the most relevant document chunks and uses Groq’s Llama3 model to generate precise answers based solely on the retrieved context.

Interactive UI: Simple and intuitive web interface built with Streamlit for easy querying and real-time display of answers and source document snippets.

