
# Northstar AI – RAG Assistant

An AI-powered document question-answering assistant built with
Retrieval-Augmented Generation (RAG).

## Overview

Northstar AI allows users to ask questions about an employee handbook
and receive answers grounded in the document's content.

## Technology Stack

- Python
- Sentence Transformers
- ChromaDB
- Hugging Face Transformers
- FLAN-T5-small
- PyPDF
- Gradio
- Google Colab

## How It Works

1. Extract text from PDF documents.
2. Split documents into overlapping text chunks.
3. Generate semantic embeddings using Sentence Transformers.
4. Store embeddings in ChromaDB.
5. Retrieve relevant information through semantic search.
6. Generate answers using FLAN-T5-small.
7. Display responses through a Gradio chatbot.

## Features

- PDF document ingestion
- Semantic search
- Vector database storage
- Context-based answer generation
- Interactive chatbot interface
- No paid OpenAI API key required

## Project Structure

- notebooks/ - Project notebook
- sample_data/ - Sample documents
- screenshots/ - Application screenshots
- requirements.txt - Dependencies

## Future Improvements

- Multiple document uploads
- Source citations
- Improved retrieval evaluation
- Persistent vector storage
- Permanent deployment

## Author

Esther Usman

AI Automation Engineer | AI Agent Developer
