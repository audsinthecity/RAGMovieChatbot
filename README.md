# RAGMovieChatbot
 RAG AI chatbot that gives movie recommendations

 This chatbot allows users to interact with a movie dataset by asking questions about movies, and the chatbot will retrieve relevant information from the dataset to answer the questions.

## Dataset
 The dataset used is from the [Internet Movie Database (IMDb)](https://huggingface.co/datasets/ShubhamChoksi/IMDB_Movies), accessed from the datasets library of the Hugging Face Hub.

## Chatbot Deployment
  The chatbot is deployed using Chainlit (https://chainlit.io/)
  Once deployed, you can view your chatbot at (http://localhost:8000/)

## Secrets
  A Hugging Face token and OpenAI API token are needed for this project. Save as a .env file in your directory.

This project uses:

- [Pandas DataFrames](https://pandas.pydata.org/docs/reference/io.html)
- [LangChain](https://python.langchain.com/v0.2/docs/introduction/)
- [OpenAI Embeddings](https://python.langchain.com/v0.1/docs/integrations/text_embedding/openai/)
- [Facebook AI Similarity Search (FAISS)](https://python.langchain.com/v0.1/docs/integrations/vectorstores/faiss/)

## Screenshot of Chainlit Deployment
<img src='https://imgur.com/a/Jz4OgCd' title='Movie RAG Chatbot' width='' alt='Movie RAG Chatbot' />
