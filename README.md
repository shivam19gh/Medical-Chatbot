# Medical Chatbot 

## Overview
This project implements a **Medical Chatbot** designed to assist users with medical-related queries by retrieving relevant information from a pre-defined set of documents. It utilizes **LangChain**, **FAISS Vector Stores**, **HuggingFace Embeddings**, and **LLama-2** to deliver precise, context-aware answers.

The system is divided into two key components:
1. **Vector Database Creation**: Prepares a searchable database of document embeddings.
2. **Query Answering**: Processes user questions and provides answers by retrieving relevant information from the database.

---

## Features
- **PDF Document Parsing**: Reads and processes PDF files for embedding generation.
- **Chunk Splitting**: Divides documents into smaller chunks for better context retrieval.
- **Generate Embeddings**: Embeddings were created using the all-MiniLM-L6-v2/sentence transformer model.
- **Efficient Vector Search**: Uses FAISS for fast and scalable similarity search.
- **Customizable Prompting**: Allows fine-tuning the format and style of responses.
- **Integration with LLama-2**: Leverages state-of-the-art large language models for natural language understanding.
- **Contextual Answers with Sources**: Ensures that every answer is backed by traceable document references.

---

## Installation

### Prerequisites
- **Python**: Version 3.8 or above.
- **Virtual Environment (Recommended)**: Use a virtual environment to isolate dependencies.

### Required Libraries
Install all necessary dependencies by running:
```bash
pip install -r requirements.txt
