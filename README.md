# RAG_using_Mistral7B_and_LangChain

## Overview

This Jupyter notebook demonstrates how to use various tools from the LangChain library to process and analyze PDF documents. It involves loading a PDF file, splitting the text into chunks, embedding the text, and using a language model for question answering. Need to run in Google Colab as there is a dependency on GPU.

## Dependencies

Before running the notebook, ensure you have the following dependencies installed:

- `huggingface_hub`
- `chromadb`
- `langchain`
- `pypdf`
- `sentence-transformers`
- `langchain-community`

You can install them using pip:

```sh
pip install huggingface_hub
pip install chromadb
pip install langchain
pip install pypdf
pip install sentence-transformers
pip install -U langchain-community

