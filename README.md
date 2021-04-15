# Arxiv Search Engine Demo
A Semantic Search Engine Built on Arxiv dataset from Kaggle. 

Tech Stack: 
* Haystack -> Provides the building blocks for the search engine. 
* Sentence-Transformers -> For computing sentence embeddings for abstract texts of the papers in the dataset, as well as for the queries.
* Faiss -> To formulate and store large embeddings as indexes on disk and perform rapid similarity search on all 50,000 documents the engine was tested on

