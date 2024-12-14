## Project Description
HelpMateAI is an intelligent assistant designed to provide support and automate tasks for users in various domains such as customer service, technical support, and personal assistance. The project aims to leverage advanced natural language processing (NLP) and machine learning (ML) techniques to deliver a seamless and efficient user experience.


## Objectives
- Develop a robust semantic search system to understand Insurance policy data and process user queries.
- Extract relevant information from PDF documents, store them in a structured format, and generate vector representations using SentenceTransformerEmbeddings or Open AI Embeddings. 
- Implement a retrieval-augmented generation (RAG) system to provide accurate and contextually relevant responses.
- Integrate the AI assistant with various communication platforms (e.g., web, mobile, chatbots).
- Ensure data privacy and security in all interactions.

## RAG Pipeline

- Embedding Layer: Turn text and tables from PDFs into dataframes and create vector representations with OpenAI's text-embedding-ada-002 model. Save these vectors in ChromaDB.
- Search and Rank Layer: Conduct a semantic search for user queries within the knowledge database, bringing up the most relevant results.
- Generation Layer: Combine the search results with the original query and a structured prompt to form coherent responses using a language model.

## Technologies Used
- Programming Languages: Python
- Frameworks: Open AI
- Databases: Croma Vector DB

## Libraries Used

- Pdfplumber
- tiktoken
- numpy 
- chromadb 
- pandas
- openai


## Contact
Created by Gaurav Dhuri


Developed as part of the NLP Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
