# HR Policy Conversation

Converse with HR policy document with Pinecone and LLAMA.

Here is how RAG works: 
![RAG](https://github.com/lindsay888/rag-hr-llm/assets/56157587/de02ebae-2408-46d4-8bfa-67d39526e7ad)

*Step 1:* 
Upload document embedding to Pinecone. You can create free account and 1 free index for the first time. 

*Step 2:*
Prepare question and document prompts to the LLM (in this case we are using LLAMA 2) to convert to natural language processing. 

# Dependencies:
pinecone
langchain
aws

We are using LLAMA 2 from AWS Bedrock and you would need to setup and install to your instances. 

Follow the steps here for setup - [Setup](https://docs.aws.amazon.com/bedrock/latest/userguide/setting-up.html)


