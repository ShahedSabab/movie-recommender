# movie-recommender
The objective is to develop a simple movie recommender model that leverages user-ratings to recommend unseen movies to the users. Based on the movie-rating patterns of users, different clusters are formed. Each cluster groups together users with similar movie choice and ratings. This knowledge is later used to provide personalized movie recommendation. The data is collected from MovieLens dataset (small) which contains 100,000 ratings of 9000 movies (rated by 600 users) and can be found in the following link:
https://grouplens.org/datasets/movielens/latest/

• Different EDA has been performed to find out genres with highest-average ratings, genres rated by most users.<br/>
• K - means clustering is performed to find out clusters with users having similar ratings.<br/>
• The value of K is determined using silhouette score.<br/>
• Personalized recommendation is given based on cluster analysis.<br/>

<img src="popular_genre.PNG" width="60%">
<img src="heatmap_user_ratings.PNG" width="70%">
<img src="determining_K_val.PNG" width="60%">
<img src="movie_recommendation.PNG" width="50%">

