# End_To_End_LLM_Langchain_Project_using_Pinecone_Vector_Database


python==3.10



Overview

This project demonstrates the setup and usage of a vector database and querying system using various tools and technologies. The system involves loading documents, processing and embedding them, and querying the database to retrieve relevant information.

Features

Document Loading: Load and extract text from PDF documents.
Text Chunking: Split documents into manageable chunks for efficient processing.
Embedding Generation: Create vector embeddings for text data using pre-trained models.
Vector Database Integration: Store and retrieve vector embeddings using Pinecone.
Query Processing: Process user queries and retrieve relevant information from the vector database.

Technologies Used

LangChain: For document processing and text splitting.
Sentence Transformers: To generate text embeddings.
Pinecone: Vector database for storing and querying embeddings.
OpenAI: Language models for various tasks.
PyPDF2: For extracting text from PDF documents.
Getting Started
Prerequisites
Python 3.10
Required libraries (see requirements.txt for a complete list)

Usage
Load and Process Documents:

Load PDF documents from a specified directory and process them into chunks.

Generate Embeddings:

Use Sentence Transformers to generate embeddings for the text data.

Set Up Pinecone Index:

Create a Pinecone index to store and manage vector embeddings.

Query Processing:

Embed user queries and use Pinecone to retrieve relevant documents based on similarity.

Retrieve Answers:

Process the results from Pinecone to generate answers to user queries.
