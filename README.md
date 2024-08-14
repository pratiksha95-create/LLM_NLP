# LLM_NLP
## Natural Language Processing/ Speech Processing: [Task 1 :: Build a chatbot that can understand context from a collection of speech data.]
project :: Clinical Text Analysis and Conversational AI 

##### Overview
This project leverages the LangChain library and Hugging Face models to analyze clinical text data, build conversational AI capabilities, and create a medical chatbot.
##### Key Features
Clinical Text Embeddings: Utilizes Hugging Face Embeddings to convert clinical text documents into numerical vectors.
##### Vector Database: 
Employs Chroma to create a vector database from the embedded documents, enabling efficient similarity search and clustering.
##### Conversational AI: 
Leverages LangChain's conversational AI capabilities, including RetrievalQA and LLMChain, for question-answering and text generation tasks.
##### Medical Chatbot: 
Builds a conversational medical chatbot using the RetrievalQA chain and conversational memory.
##### Components
Document Embeddings:HuggingFaceEmbeddings model for clinical text embeddings
Vector Database: Chroma vector database for efficient similarity search and clustering
Conversational AI: RetrievalQA and LLMChain for question-answering and text generation
Language Model: "databricks/dolly-v2-3b" model for text generation
RetrievalQA Chain: RetrievalQA for question-answering
Conversational Memory: ConversationBufferMemory for chat history storage
Usage
##### Install required libraries:
LangChain, Hugging Face Transformers, and PyTorch
##### Load and process clinical text data
Initialize the embedding model and create the vector database
Utilize the vector database for similarity search, clustering, or conversational AI tasks
Run the chatbot interaction loop
Input questions or queries, and the chatbot will respond accordingly
#### Data Loading
Replace sample speech data with your actual clinical text data
Convert text strings to Document objects
#### Models
HuggingFaceEmbeddings model: BAAI/bge-small-en-v1.5
Chroma vector database
"databricks/dolly-v2-3b" language model
#### Dependencies
LangChain library
Hugging Face Transformers library
PyTorch



Build an agent-based language models system that can take in different roles to complete tasks.
The input prompt should be a task that the system needs to complete.
The system should create task-specific workers that should interact to get the task done. 
The final output can be in text format. 

