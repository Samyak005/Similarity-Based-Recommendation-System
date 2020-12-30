

Online streaming platforms like Netflix have plenty of movies in their repositories and if we can build a recommendation system to recommend relevant movies to the users based on their historical interactions, this would improve customer satisfaction and hence improve revenue.

![Alt text](images_github/CF.png?raw=true "Title")

In this type of recommendation system, we do not need any information about the users or items. We only need user item interaction data to build a collaborative recommendation system. For example -

Ratings provided by users. For example - ratings of books on goodread, movie ratings on imdb etc
Likes of users on different facebook posts, likes on youtube videos

Use/buying of a product by users. For example - buying different items on e-commerce sites
Reading of articles by readers on various blogs

For a new user we will recommend the most popular movie i.e. the movie with the most interactions. 
While implementing the function similar_users I used cosine similarity to compute the similarity between the users.

![Alt text](images_github/collaborative_filtering.PNG?raw=true "Title")
![Alt text](images_github/cosine.PNG?raw=true "Title")