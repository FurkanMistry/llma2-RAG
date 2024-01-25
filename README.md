# llma2-RAG
This repository provides an implementation of the RAG (Retriever-Reader-Generator) model using LLAMA 2 for question answering tasks. The RAG model framework consists of three main components: retriever, reader, and generator.

Features:

Integration with LLAMA 2 for efficient question answering using pre-trained models.
Utilization of ChromaDB for indexing and retrieval of embeddings.
Demonstrates embedding generation from text using Sentence Transformers.
Implements retrieval of relevant documents based on query embeddings.
Utilizes PyPDF2 for extracting text from PDF documents.
Dependencies:

PyPDF2
Sentence Transformers
ChromaDB
Transformers
PineconeDB(optional)
Usage:

Install the required dependencies using pip.
Configure the environment and data paths.
Run the provided scripts for indexing documents and querying for answers.
Contributing:
Contributions to enhance features, fix bugs, or improve documentation are welcome! Please fork the repository, make your changes, and submit a pull request.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

References:

LLAMA 2: https://huggingface.co/meta-llama/Llama-2-7b-chat-hf]
Sentence Transformers: https://huggingface.co/sentence-transformers
ChromaDB: https://docs.trychroma.com/getting-started
PineconeDB: https://docs.pinecone.io/
