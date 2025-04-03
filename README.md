# Movie-Recommendation
This repository contains the implementation of a movie recommendation system using the MovieLens 100K dataset. The system implements three recommendation techniques: User-based Collaborative Filtering, Item-based Collaborative Filtering, and a Pixie-inspired Random Walk Algorithm. The goal of the project is to provide personalized movie recommendations based on user preferences and item similarities.

Project Overview
The MovieLens dataset consists of user ratings for a collection of movies. The recommendation system aims to predict the movies that a user might like, based on their past ratings and the ratings of similar users or movies. In addition to the traditional collaborative filtering approaches, this project explores a graph-based technique inspired by Pixie algorithms to perform recommendations using random walks on a movie similarity graph.

Key Techniques Implemented:
User-based Collaborative Filtering: Recommends movies based on the ratings of similar users.

Item-based Collaborative Filtering: Recommends movies based on the similarity between movies.

Pixie-Inspired Random Walk Algorithm: A graph-based approach to recommendations using random walks over movie similarity graphs.

Repository Structure
Movie_Recommendation.ipynb: Jupyter notebook that contains the full implementation of the recommendation system, including the three recommendation techniques.

users.csv: CSV file containing user demographic information (user ID, age, gender, occupation).

movies.csv: CSV file with metadata of movies (movie ID, title, release date).

ratings.csv: CSV file containing user ratings for movies (user ID, movie ID, rating, timestamp).

Pixie_Algorithm_Explanation.pdf: A detailed explanation of the Pixie-inspired random walk algorithm.

Recommendation_Report.pdf: A comprehensive report covering the methodology, implementation details, results, and evaluation of the recommendation system.

Instructions
Clone this repository to your local machine or open it directly on GitHub.

Open the Movie_Recommendation.ipynb Jupyter notebook to explore the implementation of the recommendation system.

Review the accompanying Pixie_Algorithm_Explanation.pdf and Recommendation_Report.pdf for more insights into the Pixie-inspired algorithm and the recommendation process.

Ensure that the dataset files (u.data, u.item, u.user) are placed in the correct directory for the notebook to run successfully.

Requirements
To run the Jupyter notebook, make sure you have the following libraries installed:

pandas

numpy

scikit-learn

matplotlib

networkx (for graph-based algorithms)

Results and Evaluation
The notebook demonstrates the outputs of the recommendation system for different approaches (user-based, item-based, and Pixie-inspired random walk). It includes visualizations and insights into the strengths and weaknesses of each method.

Conclusion
This project demonstrates how different recommendation techniques can be implemented and evaluated using the MovieLens dataset. The Pixie-inspired random walk algorithm adds a unique graph-based approach to the recommendation process, complementing traditional collaborative filtering methods.
