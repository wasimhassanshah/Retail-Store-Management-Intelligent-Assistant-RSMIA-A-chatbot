# Retail-Store-Management-Intelligent-Assistant-RSMIA-A-chatbot
Retail Store Management Intelligent Assistant (RSMIA): A chatbot for retail inventory and sales insights.

** Purpose:
  Empowered store managers to query MySQL

- Description
    Designed and developed a cutting-edge LLM-based Q&A system leveraging Google Palm LLM, Hugging
Face embeddings, Streamlit for UI, Langchain framework, and Chromadb as a vector store. Utilized few-shot learning to enable the system to generate accurate SQL queries from natural language inputs.
(Streamlit, Langchain, Google Palm LLM, Face, Chromadb, Few-shot learning, PyCharm)

- Project Highlights
1. AtliQ Tees is a t shirt store that sells Adidas, Nike, Van Heusen and Levi's t shirts
Their inventory, sales and discounts data is stored in a MySQL database

- Tools used
Google Palm LLM
Hugging face embeddings
Streamlit for UI
Langchain framework
Chromadb as a vector store
Few shot learning
In the UI, store manager will ask questions in a natural language and it will produce the answers

- Sample Questions
How many total t shirts are left in total in stock?
How many t-shirts do we have left for Nike in XS size and white color?
How much is the total price of the inventory for all S-size t-shirts?
How much sales amount will be generated if we sell all small size adidas shirts today after discounts?

- Project Structure
main.py: The main Streamlit application script.
langchain_helper.py: This has all the langchain code
requirements.txt: A list of required Python packages for the project.
few_shots.py: Contains few shot prompts
.env: Configuration file for storing your Google API key.




