# Objective 

The aim of this project is to create a web-based recommendation system that utilizes machine learning algorithms to provide users with personalized movie recommendations. These recommendations will be based on user preferences related to movie overviews, genres, and the cast and crew, ultimately presenting the top 5 most relevant movie suggestions.

# Data Description

Two datasets sourced from Kaggle are employed in this project, both originally obtained from the TMDB website. 
1. The first dataset, comprises information such as movie genres, overviews, and taglines. 
2. The second dataset, contains details about the cast and crew members associated with each movie.

Dataset link :  https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

# Data Preprocessing

1. Cleaning  different columns such as cast, crew, overview, keywords, and genres to create one tag column.
   
    ![Screenshot (120)](https://github.com/MinalJain17/Movie-Recommender-System/assets/132137245/4d397a7d-40e1-45b0-bdd9-6aad6bf1b2ac)

3. Eliminating Stop Words and Conducting Stemming: Utilizing Scikit-Learn(vectorization) and NLTK to remove stop words and apply stemming.
   
    ![Screenshot (121)](https://github.com/MinalJain17/Movie-Recommender-System/assets/132137245/d86f3323-74b2-41b0-bb20-f5bc045fd889)

# Machine Learning Modeling

Developed a recommender function that efficiently suggests the top 5 relevant movies based on cosine similarity. And stored it with the help of a pickle library.

   ![Screenshot (123)](https://github.com/MinalJain17/Movie-Recommender-System/assets/132137245/b80938f1-3da8-4ad2-90b0-c3ccc0c0ea2c)

# Web Page

Select the Movie from the dropdown list.

![1](https://github.com/MinalJain17/Movie-Recommender-System/assets/132137245/b8cfb864-69ea-484a-a967-cb05a0cf7e49)

Provide a list featuring the top 5 recommended movies, each with a displayed logo.

![2](https://github.com/MinalJain17/Movie-Recommender-System/assets/132137245/75be4efe-e6a3-42e8-8331-30217497d0a3)

# Challenges and Learning

1. Exploring Feature Selection Complexity: Exploring the complexities of selecting the right attributes to enhance movie prediction accuracy.
2. Incorporating the Streamlit library and establishing a virtual environment.

