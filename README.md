# Movie-Recommender (Python - Machine Learning)

This is a content-based Movie Recommendation System which uses the concepts of 'TF-IDF Vectorization' and 'Cosine-Similarity'.
The user inputs a movie name and the system suggests 10 movies based on the similarities between their genres, keywords, tagline, cast and director.

# Dataset

File: [`movies.csv`](movies.csv)   
The file contains metadata of popular movies which includes genres, cast, director, keywords, etc.
Dataset was taken from Kaggle.

# Workflow

The system
1. Cleans and combines selected text-based features from the dataset of movies.
2. Applies TF-IDF Vectorizer to convert text into numerical feature vectors.
3. Calculates cosine similarity between movie vectors.
4. Recommends 10 most similar movies based on input of user.

# Credits

The project is based on a tutorial by 'Siddhardhan'(https://www.youtube.com/watch?v=7rEagFH9tQg&t=746s).  
This tutorial provided valuable insights and helped me develop a strong foundational understanding of content-based recommendation systems.

# Project Status

This is the initial version based on a tutorial.  
Planned improvements include:
- Refactoring code into reusable functions
- Building an interactive UI using Streamlit

# Results

<img width="355" height="375" alt="Screenshot 2025-07-12 225954" src="https://github.com/user-attachments/assets/a5a6ef7a-d9e0-429c-abc5-1cca67ab192a" />


