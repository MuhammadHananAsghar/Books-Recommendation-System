# Books Recommendation System

Kaggle Dataset: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

OverView:

The project involves building a book recommendation system using collaborative filtering techniques on a dataset containing information about books, users, and their ratings. The dataset comprises three main components: "Books.csv," "Users.csv," and "Ratings.csv." Initially, the data is loaded into pandas DataFrames and explored to understand its structure. Preprocessing steps include merging relevant datasets, calculating popularity-based metrics such as the number of ratings and average ratings per book, and identifying the most popular books based on these metrics. 

Following this, collaborative filtering techniques are applied to generate personalized recommendations for users based on their past ratings. This involves filtering users who have provided a minimum number of ratings and books that have been rated a certain number of times. A pivot table is then created to represent users' ratings for different books. Cosine similarity is computed between books based on their user ratings, and similar books are recommended for a given book input by the user.

The project aims to provide users with personalized book recommendations by leveraging collaborative filtering techniques and book rating data. It demonstrates the application of data preprocessing, exploratory data analysis, and machine learning algorithms to build a recommendation system tailored to users' preferences.
