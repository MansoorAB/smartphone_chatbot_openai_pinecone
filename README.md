# smartphone_qna_openai_pinecone

## Purpose

1. The aim of this use case is to build a question answer chatbot for various smartphones
2. We will load the data from various smart phone user manuals 
3. Convert the data into text chunks
4. Load the environment variables 
5. Use OpenAIEmbeddings to convert the text chunks to embeddings
6. Create a pinecone index with appropriate dimensions
7. Store the embedding in Pinecone Vector database
8. Use and OpenAI LLM model 


## Please follow the below steps to execute this note book

1. Create a conda environment
```bash
conda create -n smartphone_qna python=3.9 -y
```
2. Install Jupyter notebook
```bash
conda install jupyter notebook
```
3. Load the rest of the dependencies
```bash
pip install langchain
pip install pinecone-client
pip install pypdf
pip install openai
pip install tiktoken
pip install python-dotenv
pip install -U langchain-pinecone
pip install langchain_openai
```
4. Run the .ipynb file for the various execution steps

## Next Steps

An end to end UI interface can be built with streamlit app
