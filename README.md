# RAG 

This project implements a Retrieval-Augmented Generation (RAG) system from scratch, enabling you to query large documents (like PDFs) using a local Large Language Model (LLM).

## 📚 Overview

The pipeline allows you to:

- Ingest and parse large PDF documents.
- Chunk and embed text using Sentence-BERT.
- Store embeddings in a local vector store.
- Retrieve relevant chunks based on user queries.
- Generate answers using a local LLM (e.g., LLaMA 2) with the retrieved context.

## 🛠️ Features

- **PDF Parsing**: Utilizes `PyMuPDF` to extract text from PDFs.
- **Text Chunking**: Splits documents into manageable chunks for embedding.
- **Embedding**: Employs `sentence-transformers` to convert text chunks into embeddings.
- **Vector Store**: Stores embeddings locally for efficient retrieval.
- **Retrieval**: Retrieves relevant chunks based on semantic similarity to the query.
- **Generation**: Uses a local LLM to generate answers based on retrieved context.

## 🧰 Tech Stack

- Python 3.11
- [PyMuPDF (`fitz`)](https://pymupdf.readthedocs.io/)
- [spaCy](https://spacy.io/)
- [SentenceTransformers](https://www.sbert.net/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [PyTorch](https://pytorch.org/)
- [matplotlib](https://matplotlib.org/)
- [tqdm](https://tqdm.github.io/)

