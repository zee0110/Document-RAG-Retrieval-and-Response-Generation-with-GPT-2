# Document-RAG-Retrieval-and-Response-Generation-with-GPT-2

### README

#### Document Retrieval and Response Generation with GPT-2

This code demonstrates a document retrieval and response generation system using a combination of Sentence Transformers, FAISS (Facebook AI Similarity Search), and GPT-2 (Generative Pre-trained Transformer 2). It allows users to input queries, retrieve relevant documents based on the queries, and generate responses using a pre-trained GPT-2 model.

#### Prerequisites

Ensure you have Python installed on your system along with the necessary libraries:
- torch
- transformers
- sentence-transformers
- numpy
- faiss-cpu

You can install the required libraries using pip:

```
pip install torch transformers sentence-transformers numpy faiss-cpu
```

#### Usage

1. Clone the repository or download the code files.
2. Make sure you have the required dataset file or documents for retrieval (e.g., "states.txt").
3. Run the code using a Python interpreter.
4. The code loads pre-trained models for GPT-2 and Sentence Transformers.
5. It builds a FAISS index for efficient document retrieval.
6. Users can input queries, and the system retrieves relevant documents based on the queries.
7. It then generates responses using the retrieved documents and the GPT-2 model.
8. The generated response is displayed to the user.
9. Users can continue to input queries until they enter 'quit' to exit the system.

#### Features

- Utilizes pre-trained models for document embedding (Sentence Transformers) and response generation (GPT-2).
- Implements efficient document retrieval using FAISS (Facebook AI Similarity Search).
- Allows users to input queries for document retrieval and response generation.
- Generates responses based on the retrieved documents and user queries.
- Provides an interactive interface for continuous user interaction.

