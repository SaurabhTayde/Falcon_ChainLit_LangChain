# Chat UI using Falcon 7B, LangChain and Chainlit

Chatbot in this respository is created using LangChain Framework, Open source Falcon 7B Instruct model and ChainLit. API of open source LLM is taken from Hugging Face Hub. Deployment is done using ChainLit which provides great Aesthetic UI for AI to user communication.

This repository can run in Github codespaces or locally. Please add your huggging face API token and input it in .env (Rename example.env to .env). After running 'requirements.txt' please run following command to start the chat UI:

chainlit run langchain_falcon.py -w