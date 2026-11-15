# LangChain Vector Store Operations with ChromaDB

This project demonstrates how to create and manage a vector store using **LangChain, Google Gemini Embeddings, and ChromaDB**.

## Features

- Generate embeddings using `gemini-embedding-001`.
- Store documents in ChromaDB.
- Perform semantic similarity searches.
- Retrieve documents with similarity scores.
- Filter search results using metadata.
- Add, update, and delete documents.
- Retrieve stored documents, embeddings, and metadata.

## Tech Stack

- Python
- LangChain
- Google Gemini Embeddings
- ChromaDB
- LangChain Chroma
- Tiktoken

## Installation

```bash
pip install -U langchain langchain-community langchain-google-genai langchain-chroma chromadb tiktoken pypdf
```

## Setup

Set your Google API key before running the notebook:

```python
import os
from getpass import getpass

os.environ["GOOGLE_API_KEY"] = getpass("Enter your API Key: ")
```

## Concepts Covered

1. Document creation
2. Embedding generation
3. Vector store initialization
4. Document insertion
5. Similarity search
6. Similarity score retrieval
7. Metadata filtering
8. Document updating and deletion

## Learning Objective

To understand how vector databases store document embeddings and enable semantic search, which are essential concepts in building Retrieval-Augmented Generation (RAG) applications.

## 🤝 Feedback & Contributions

Suggestions, feedback, and discussions are always welcome!

If you find this repository useful, consider giving it a ⭐.

---

## 👩‍💻 Author

**Jiya Sheikh**

GitHub: [@JiyaSheikh06](https://github.com/JiyaSheikh06)
