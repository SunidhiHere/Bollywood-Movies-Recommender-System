<img width="1942" height="595" alt="ChatGPT Image Jun 15, 2026, 10_22_18 PM" src="https://github.com/user-attachments/assets/dc915db2-2deb-47a6-946f-2bc652eccd77" />

## Introduction
The Bollywood Movie Recommender System is a content-based recommendation project designed to help users discover movies that match their interests and viewing preferences. With the rapid growth of digital entertainment platforms, finding relevant movies from a large collection can be challenging. This project addresses that problem by providing personalized movie recommendations based on the similarity of movie plot summaries and other textual features.

The system utilizes Natural Language Processing (NLP) techniques to analyze movie descriptions and extract meaningful information from textual data. After preprocessing the data, TF-IDF (Term Frequency-Inverse Document Frequency) vectorization is applied to convert movie plots into numerical feature vectors. Cosine Similarity is then used to measure the similarity between movies and identify those with comparable themes, genres, and storylines.

When a user selects a movie, the system recommends a list of similar Bollywood movies, enabling users to discover new content efficiently. The final recommendation engine can be integrated into a user-friendly web application using Streamlit, providing an interactive and engaging experience for movie enthusiasts.

## Project Pipeline
Data Collection & Understanding: Imported the Wiki Movie Plots dataset and selected relevant Bollywood movie information such as titles, genres, and plot summaries for recommendation generation.
Data Preprocessing: Cleaned the dataset by handling missing values, removing duplicates, and preprocessing plot descriptions through text cleaning and normalization techniques.
Exploratory Data Analysis (EDA): Analyzed movie distributions, genres, and common patterns within plot summaries to better understand the dataset.
Feature Engineering & Similarity Calculation: Converted movie plots into numerical vectors using TF-IDF and calculated Cosine Similarity scores to measure the similarity between movies.
Recommendation Engine Development: Built a content-based recommendation system that identifies and suggests movies with similar storylines and themes based on user-selected movies.
Deployment: Integrated the recommendation model into a Streamlit web application, allowing users to receive personalized Bollywood movie recommendations through an interactive interface.

## About Dataset
The dataset used in this project is Wiki Movie Plots, which contains information about thousands of movies collected from publicly available Wikipedia sources. For this recommender system, Bollywood movie records were extracted and utilized to build personalized movie recommendations.
The dataset includes important attributes such as movie title, release year, genre, origin/industry, and plot summaries. Among these features, the plot description serves as the primary source of information for understanding the storyline and thematic content of each movie.
Since recommendation quality heavily depends on textual information, the movie plot summaries were used to identify similarities between films. These descriptions provide insights into the narrative, characters, themes, and overall context of each movie.
Before model development, the dataset underwent preprocessing steps such as handling missing values, removing duplicate records, and cleaning textual data. This ensured consistency and improved the effectiveness of the recommendation engine.
The final processed dataset serves as the foundation for generating movie recommendations by transforming plot summaries into numerical representations and measuring similarity between movies using Natural Language Processing (NLP) techniques.

## EDA
## MOdel
## Model evaluation
## Conclusion
##Sources
