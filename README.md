# RAG-using-LLama2-and-ChromaDB
Use Llama 2.0, Langchain and ChromaDB to create a Retrieval Augmented Generation (RAG) system. This will allow us to ask questions about our documents (that were not included in the training data), without fine-tunning the Large Language Model (LLM).
When using RAG, if you are given a question, you first do a retrieval step to fetch any relevant documents from a special database, a vector database where these documents were indexed. 
