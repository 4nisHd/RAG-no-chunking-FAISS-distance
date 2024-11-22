In this project I used Gemini Pro for text generation with Retrieval Augmented Generation (RAG) with document preprocessing, semantic search, and large language model inference.
  
 **Document Preprocessing**: Extracted and processed document content using **LangChain** and **PyPDFLoader**.  
**Dense Vector Embeddings**: Created dense vector embeddings of each page in the document using **Sentence Transformers**.  
**Similarity-Based Retrieval**: Used **FAISS** for similarity search and clustering of dense vectors.  
  
  After encoding a query into an embedding with Sentance transformer, I used FAISS to search for the most relevant document parts.
  The RAG pipeline retrieves and outputs the closest document based on its similarity score (distance).
