# What-kind-of-movies-you-like-to-watch?
Movie Recommendation using Collaborative and Content Based Filtering

There are two types of recommendation systems, Content-Based and Collaborative Filtering. Collaborative Filtering focuses on the similarity attribute of the users and it finds people with similar tastes based on a similarity measure from the large group of users. In contrast, content-based recommendation systems focus on the attributes of the items and give you recommendations based on the similarity between them.

In Collaborative Filtering, this recommendation system makes predictions of what might interest a person based on the taste of many other users. It assumes that if person X likes comedy movies, and person Y likes comedy movies and family movies, then person X might like family movies as well. There are two types of this recommender filter:

User-User: It identifies other people with similar tastes to a target user and combines their ratings to make recommendations for that user.

Item-Item: Itidentifies global product associations from user ratings, but uses these product associations to provide personalized recommendations based on a user's own product ratings

In Content-Based Filtering, this recommendation system focuses on the products themselves and recommends other products that have similar attributes. It relies on the characteristics of the products themselves, so it doesn’t rely on other users to interact with the products before making a recommendation.

In this notebook, I will only implement the collaborative recommender system, where I will evaluate the user and item recommender to see which one performs better.

The MovieLens Dataset

The MovieLens datasets are full of data describing how people rate movies. As it turns out, these datasets have been useful to lots of folks, from recommender systems researchers to the readers of popular-press programming books. It was collected by GroupLens researchers over various periods of time and by far the most popular when it comes to implementing a recommender system.

These datasets will change over time, and are not appropriate for reporting research results. I choose to use the smallest datasets with 100,000 ratings with 9,000 movies by 700 users. They were last updated 10/2016.
