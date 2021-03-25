```
Please note that this repository is incomplete.
```

# Movie Recommendation System

To help customers choose movies to watch, companies such as Netflix have developed world-class movie recommendation systems. You can also find large scale recommendation systems in retail or music streaming.

The goal of this project is to build a model that provides the top 5 movie recommendations to a user, based on their ratings of other movies.

## Data Understanding

Data is sourced from the [MovieLens](https://grouplens.org/datasets/movielens/latest/) dataset from the GroupLens research lab at the University of Minnesota.

This project uses the "small" dataset containing 100,000 ratings and 3,600 tag applications applied to 9,000 movies by 600 users. Users were selected at random for inclusion. All selected users rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

## Collaborative Filtering

Collaborative filtering systems use a collection of user data such as ratings to make recommendations. A common problem with this approach is the "cold start problem" where the system cannot draw inferences for users or items for which it hasn't gained sufficient information. This problem can be addressed by using a hybrid of content-based filtering.

## Evaluation

[FastML - Evaluating Recommender Systems](http://fastml.com/evaluating-recommender-systems/)
