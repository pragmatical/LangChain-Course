# LangChain-Course

Get started by:
* running pip install -r requirements.txt
* create .env file with the following contents:
  
  ``` bash
  OPENAI_API_KEY=''
  CHATGPT_MODEL='gpt-35-turbo'
  OPENAI_API_BASE='https://<instance>.openai.azure.com'
  OPENAI_API_VERSION='2023-09-15-preview'
  HUGGINGFACEHUB_API_TOKEN=''
  SERPAPI_API_KEY=''
  EMBEDDINGS_MODEL='text-embedding-ada-002'
  PINECONE_API_KEY=''
  PINECONE_ENV=''
  ```

You may need to create accounts at the different sites used in the labs:

<https://huggingface.co/>
<https://serpapi.com/>
<https://www.pinecone.io/> - the notebook requires an instance of a vector db to be created, pinecone allows for one free instance, the instance will need to have 1536 dimensions to work with the embeddings produced by text-embedding-ada-002 model
