# movie-recommender
A objective is to develop a simple movie recommender model which leverages user-ratings to recommend new movies to the users. Based on the ratings of users, different clusters are formed. Each cluster groups together users with similar movie choice and ratings. This knowledge is later used to provide personalized movie recommendations. The data is collected from MovieLens dataset (small) which contains 100,000 ratings of 9000 movies rated by 600 users and can be found in the following link:
https://grouplens.org/datasets/movielens/latest/

• Different EDA has been performed to find out popular genres, highest number of users interested to a particular genre.
• K - means clustering is performed to find out clusters with users having similar ratings.
• The value of K is determined using silhouette score.
• Personalized recommendation is given based on cluster analysis.
