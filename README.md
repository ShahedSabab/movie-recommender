# movie-recommender
The objective is to develop a simple movie recommender model that leverages user-ratings to recommend unseen movies to the users. Based on the movie-rating patterns of users, different clusters are formed. Each cluster groups together users with similar movie choices and ratings. This knowledge is later used to provide personalized movie recommendations. The data is collected from MovieLens dataset (small), which contains 100,000 ratings of 9000 movies (rated by 600 users).The data can be found in the following link: <br>
https://grouplens.org/datasets/movielens/latest/

• Different EDA has been performed to find out genres with the highest-average ratings, genres rated by most users.<br/>
• K - means clustering is performed to find out clusters with users having similar ratings.<br/>
• The value of K is determined using the Silhouette score.<br/>
• Personalized recommendation is given based on cluster analysis.<br/>

### Popular Genre
<img src="popular_genre.PNG" width="60%">

### Determining the value of k for K Means (Elbow method)
<img src="determining_K_val.PNG" width="60%">

### Visualizing User Ratings in a Cluster
<img src="visualize_user_cluster.PNG" width="70%">

### Recommending Movies to a User
<img src="movie_recommendation.PNG" width="50%">

# How to run:
Please check the Movie_Recommender.ipynb file for the detailed analysis.
