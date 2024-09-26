Assessment Code

The Code share above is a Simple representation of RAG Implementattion using OpenAI and Langchain at its core and FAISS as the database . 

The Code take a PDF input as a Knowledge base
We conver that PDF into smaller set of files calling document 
then we initialize our API Keys : ***It me not work cause the environment file is not shared in this repo***
we then convert each document into numerical representation using OpenAI Embeddings . 
Once converted then we make a retriever out of it which will fetch document from the Knowledge base . 
later we defime an LLM and a prompt and make a chain out of it 
lastly is to make a call to the chain and send the input for rhe prompt 

