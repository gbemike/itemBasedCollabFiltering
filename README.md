# itemBasedCollabFiltering

This notebook looks to practicalize Item Based Collaborative filtering using a dataset of movies which include the title and ids of the movie as well as a ratings dataset which includes all ratings given by a user to a movie.

To begin, I want to explain what collaborative filtering is all about. In collaborative we observe the interactions between users and items to build knowledge on user preference and be able to find similar users to recommend to. We want to be able to find similar users based on their interactions with items, the space which has the interactions between a user and an item is called the user interaction matrix. For us to get similar users we have to use explicit feedback gotten from users in the form of ratings. So every item has a rating given by a user. For example, different movies get ratings from different people, thats how it would look in our dataset.

As said earlier this notebook is concerned with specifically item based collaborative filtering, which involves finding the similarity of items with each other. The similarity can be found using different methods or formulas in this notebook, cosine similarity will be used. 
