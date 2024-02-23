# Jen-rag-chatbot-aws-bedrock
This sample repository provides a sample code for using RAG (Retrieval augmented generation) method relaying on Amazon Bedrock Titan Embeddings Generation 1 (G1) LLM (Large Language Model), for creating text embedding that will be stored in FAISS with vector engine support for assisting with the prompt engineering task for a more accurate response from LLMs.

After we successfully loaded embeddings into FAISS, we will then start querying our LLM, by using LangChain. We will ask questions, retrieving similar embedding for a more accurate prompt.

1. Colab notebook version: https://github.com/Jencheng1/Jen-rag-chatbot-aws-bedrock/blob/main/Jennifer_cheng_aws_bedrock_rag_colab_fraud_qa.ipynb
2. Used Streamlit as UI: https://github.com/Jencheng1/Jen-rag-chatbot-aws-bedrock/blob/main/rag_chatbot_app.py
3. Used Langchain and AWS Bedrock as back-end for RAG: https://github.com/Jencheng1/Jen-rag-chatbot-aws-bedrock/blob/main/jen_rag_chat_lib.py
   

