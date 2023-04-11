# collaborative-filtering

## Project Overview 

### Goal
The goal of the project is to create a movie recommendation tool based on existing users' ratings for an imginary startup business, "Ripe Pumpkins" using Apache Spark in R. 

In Collaborative recommendation (collaborative filtering) we make predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating). The underlying assumption is that if a user A has the same opinion as a user B on an issue, A is more likely to have B's opinion on a different issue x than to have the opinion on x of a user chosen randomly.

### Dataset 

The full dataset contains 27,000,000 ratings and 1,100,000 tag applications applied to 58,000 movies by 280,000 users. It includes tag genome data with 14 million relevance scores across 1,100 tags.

### Execution Phases
Phase 1: Loading and parsing the dataset. Persisting the resulting RDD for later use.

Phase 2: Building the recommender model using the complete dataset. Persist the dataset for later use.

Phase 3: Testing the recommender by adding two new users and their preferences. Run the recommender to produce movie recommendations. 

#### Dataset Source: 
https://grouplens.org/datasets/movielens/ 
