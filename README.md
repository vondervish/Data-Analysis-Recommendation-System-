# Netflix_Recommendation_system
Netflix Recommendation System using Sentence Transformers

This project implements a content-based recommendation system for Netflix titles using Sentence Transformers. The system leverages semantic embeddings of movie and TV show descriptions to identify and recommend the top 5 most similar titles.

Key Features:
	
    •	Sentence Transformer Embeddings: Utilizes pre-trained SentenceTransformer models (e.g., all-MiniLM-L6-v2) to generate high-quality embeddings for descriptions.
	•	Cosine Similarity: Computes pairwise cosine similarity to rank and recommend similar titles.
	•	Attribute-Based Filtering: Supports filtering recommendations by attributes like type (Movie/TV Show) and rating to refine results.
	•	Scalable Architecture: Precomputed embeddings ensure efficient recommendations, suitable for large datasets.

Workflow:
    
    1.	Data Preprocessing: Cleaned and prepared the dataset by removing duplicates and handling missing descriptions.
    2.	Embedding Generation: Encoded descriptions into semantic embeddings using Sentence Transformers.
    3.	Similarity Computation: Calculated cosine similarity between all embeddings to measure content similarity.
    4.	Recommendation Logic: Built a function to retrieve the top 5 similar titles for any given movie or TV show, with optional attribute filtering.
