# IMDB_movies_recommendation_system

## Develop a movie recommendation system based on customer ratings 

## Part 1 multi-armed bandit approach (a good way to overcome the 'cold start' problem in the movie recommendation system):
1. Design a strategy to solve your partial-feedback multi-armed bandit problem with stochastic and non-stochastic algorithms like using UCB1, EXP3, Thompson and MWU;
2. Design a strategy to solve your full-feedback multi-armed bandit problem with stochastic and non-stochastic algorithms like UCB1, Thompson and MWU algorithms;
3. Analyze how the recommendation probabilities for movies changes over time. For our analysis, we will focus on top 10 highly rated movies by devising any metric to pick these movies. After making the movie selection, plot the recommendation probabilitie.

## Part 2 k-means appaoach:
1. Applied feature engineering with normalization and PCA reduction on IMDb dataset with 1.8 millions movies;
2. Implemented Online K-Means Clustering based on Euclidean distance;
3. Develop assumption free K-MC2 seeding method to reduce 12% training time;
