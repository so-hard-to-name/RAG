# RAG.ipynb – Retrieval-Augmented Generation Notebook

This repository contains **`RAG.ipynb`**, a Jupyter Notebook demonstrating a Retrieval-Augmented Generation (RAG) workflow. The notebook was originally developed and/or run in **Google Colab** and is intended to be compatible with local Jupyter environments.

---

## Overview

Retrieval-Augmented Generation (RAG) combines:

- Information retrieval (searching a knowledge base or documents)
- Text generation (using a large language model)

The notebook walks through:

- Loading and preparing data  
- Creating embeddings  
- Retrieving relevant context  
- Generating answers grounded in retrieved information
- Show the sources of the result from the provided file(s)

---

## Requirements

The notebook is designed to run in **Python 3.9+**.

Typical dependencies include:

- numpy  
- langchain
- langchain-community
- langchain-huggingface
- pandas
- kaggle
- pypdf
- faiss-cpu or faiss-gpu  
- ipywidgets (optional, for interactivity)

The first step in code is to install dependencies. 

---

## Running the Notebook
### Google Colab (Recommended)
- Upload RAG.ipynb to https://colab.research.google.com
- Open the notebook
- Upload a file to the env and modify the `pdf_path` in the note book. 
- Run cells sequentially
Colab provides a preconfigured environment and GPU support if needed.

---

## Common Issues
With CPU, the answer process will need around 5 - 10 minutes. With GPU, it will need 1.5 - 3 minutes
