# Tutorial to build RAG-based LLM Application using LangChain Ecosystem

This repository contains a complete tutorial for building a Retrieval-Augmented Generation (RAG)-based Large Language Model (LLM) application using the LangChain ecosystem.

![image](https://github.com/Abhishekvidhate/TUTORIAL-RAG-based-LLM-APPs/assets/120262589/aafa95cf-1946-494e-ae4d-8e9f63027c88)

## Overview

The tutorial covers the following aspects:
- Data loading and transformation required for LLM training and inference.
- Text preprocessing, including splitting and chunking, using the LangChain framework.
- Embedding generation using HuggingFace's models integrated with LangChain.
- Model inference using the LLAMA3 model from Groq for its fast inference capabilities.
- Utilizing AstraDB from DataStax as a vector database for storing embeddings.

## Frameworks and Libraries

### LangChain
LangChain is used for data loading, transformation, and integration with HuggingFace models. More information can be found at:
- [LangChain](https://www.langchain.com/)

### HuggingFace Transformers
used huggingface's Sentence-transformers for free embedding of text to vectors
- [HuggingFace Transformers GitHub](https://github.com/huggingface/transformers)
- [HuggingFace Transformers Documentation](https://huggingface.co/transformers/)

![HuggingFace Transformers](images/huggingface_transformers.png)

### Groq LLAMA3 Model
Groq is utilized for its fast inference capabilities. More information can be found at:
- [Groq GitHub](https://groq.com/)
- [LLAMA3 Model Information](https://llama.meta.com/llama3/)

![Groq LLAMA3](images/groq_llama3.png)

### AstraDB by DataStax
AstraDB is used as a vector database for storing embeddings. More information can be found at:
- [DataStax AstraDB](https://www.datastax.com/products/astra)

![DataStax AstraDB](images/datastax_astradb.png)

## Setup and Installation
 just run jupyter notebook in google colab ( free tier supported )

