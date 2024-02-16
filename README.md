ChatBot Text-To-Answer

Python script designed for a specific task involving natural language processing (NLP) and conversational retrieval using Langchain and Google Generative AI. Here's a brief breakdown of what it does:

1. Installation: It installs several Python packages required for the task using `pip install`.
2. Setting up Google API Key: It sets up the Google API key required for accessing Google services.
3. Loading PDF Documents: It loads PDF documents from a specified directory using Langchain's `PyPDFDirectoryLoader`.
4. Splitting Documents: It splits the loaded documents into smaller text chunks using Langchain's `RecursiveCharacterTextSplitter`.
5. Embedding Documents: It embeds the split documents using Google Generative AI embeddings.
6. Creating Vector Store: It creates a vector store (database) using Langchain's `Chroma` from the embedded documents.
7. Prompt Setup: It sets up a prompt template for generating answers based on a given question and context.
8. Retrieval Setup: It sets up retrieval of relevant context using the vector store.
9. Chaining Components: It chains together components for processing user queries, generating responses, and managing chat history.
10. User Interaction: It sets up a simple user interface using IPython widgets for users to interact with the chatbot.
    
In summary, this script seems to be a part of a larger system for building a conversational AI chatbot that can answer questions based on provided contexts, particularly from PDF documents, utilizing Langchain and Google Generative AI.
