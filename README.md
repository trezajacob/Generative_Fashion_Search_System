# Generative_Fashion_Search_System
## 1.	Objectives
Primary Objective: To create a generative search system capable of searching a vast array of fashion product descriptions and recommending appropriate choices based on user queries.
Secondary Objectives:
•	To develop a fashion query response system that utilizes AI models to provide detailed and user-friendly responses to fashion-related queries.
•	To enhance user experience by generating informative and contextually relevant answers.
•	To assist users in finding fashion items that match their preferences.
## 2.	Data source:
Myntra Fashion Dataset of Women with Text and Images
URL: https://www.kaggle.com/datasets/djagatiya/myntra-fashion-product-dataset
## 3.	Design & Implementation: 
![image](https://github.com/user-attachments/assets/1e9c24bb-4a64-4c2e-a7bb-39b5d2b1b257)

 
The project involves three main layers: the Embedding Layer, the Search and Rank Layer, and the Generation Layer.
### •	Embedding Layer: 
This layer is crucial for understanding the meaning of the text and its semantic relationship to the query. It involves two key processes:
o	Text Processing: Cleaning and preparing the text data to ensure consistency and readability.
o	Chunking & Embeddings: Dividing the text into manageable chunks and generating embeddings to represent the semantic content of the text.
### •	Search and Rank Layer:
Responsible for retrieving relevant fashion items from the dataset based on keyword matching or predefined criteria. It includes:
o	Semantic Search with Cache: Performing searches that consider the semantic meaning of the query and caching results to improve efficiency.
o	Re-Ranking: Refining the search results to prioritize the most relevant items.
### •	Generation Layer: 
Utilizes advanced AI models like GPT-4 to generate detailed, contextually relevant responses to user queries. This layer dynamically produces natural language responses, enhancing the overall user experience.
