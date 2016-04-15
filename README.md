# Recommender Case Study


**Goal**:
Build a movie recommender.

**Data**:
[MovieLens dataset](http://grouplens.org/datasets/movielens/), which includes
* movie information (`data/movies.dat`)
* user information (`data/users.dat`)
* users' ratings

**Model Tool**:
* Dato GraphLab

**Quick Evaluation**:
* Predict rating for each user-movie combination &rarr; take top 5% of movies for each user &rarr; average the actual ratings for those movies
    * try to maximise average rating; not testing against anything
