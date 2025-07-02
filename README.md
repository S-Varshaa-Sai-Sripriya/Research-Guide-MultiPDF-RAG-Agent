## Research Guide with RAG Agent

Overview

Research Guide is a Streamlit-based application that helps researchers interact with their PDF documents through a Retrieval-Augmented Generation (RAG) agent. Users can upload multiple PDF files, process them, and then ask questions about the content. The application uses natural language processing to provide answers based on the uploaded documents.


![Research Guide](https://github.com/user-attachments/assets/ad7ee23b-6ec6-4065-9e80-22e6b498f185)


Features

    PDF Processing: Extract text from multiple PDF documents

    Text Chunking: Split large documents into manageable chunks for processing

    Vector Storage: Create a searchable vector store using HuggingFace embeddings

    Conversational AI: Ask questions and get answers based on your documents

    Chat History: View the conversation history with the AI assistant

Technical Details

    Backend: Python with Streamlit

    Text Processing: PyPDF2 for PDF extraction, LangChain for text splitting

    Embeddings: HuggingFace Instructor embeddings

    Vector Store: FAISS for efficient similarity search

    Language Model: Google's Flan-T5-XXL from HuggingFace Hub

Acknowledgements

This project was developed using various online resources and open-source technologies. Special thanks to the online resource, open-source community for providing the foundational tools and libraries that made this application possible.

Future Enhancements

    Support for additional document formats (DOCX, TXT, etc.)

    Improved chunking strategies for better context retention

    Option to choose between different language models

    Enhanced UI with document preview and management features# Research-Guide-MultiPDF-RAG-Agent

> 📚 This project is a learning-based implementation
