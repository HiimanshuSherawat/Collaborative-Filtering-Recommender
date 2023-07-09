# Collaborative-Filtering-Recommender
Collaborative Filtering Recommender System

Collaborative filtering is a family of algorithms where there are multiple ways to find similar users or items and multiple ways to calculate rating based on ratings of similar users.

With user-based collaborative filtering, a visitor to Amazon would be matched with other customers who had similar purchase histories, and those purchase histories would suggest recommendations for the visitor.

Recommender systems are an integral part of many online systems. From e-commerce to online streaming platforms. Recommender systems employ the past purchase patters on it's user to predict which other products they may in interested in and likey to purchase. Recommending the right products gives a significat advantage to the business. A mojor portion of the revenue is generated through recommendations.

The Collaborative Filtering algorithm is very popular in online streaming platforms and e-commerse sites where the customer interacts with each product (which can be a movie/ song or consumer products) by either liking/ disliking or giving a rating of sorts. One of the requirements to be able to apply collaborative filtering is that sufficient number of products need ratings associated with not them. User interaction is required.

This notebook walks through the implementation of collaborative filtering using memory based technique of distnce proximity using cosine distances and nearest neighbours.


About the data¶
This is a dataset related to over 2 Million customer reviews and ratings of Beauty related products sold on Amazon's website.

It contains:

the unique UserId (Customer Identification),
the product ASIN (Amazon's unique product identification code for each product),
Ratings (ranging from 1-5 based on customer satisfaction) and
the Timestamp of the rating (in UNIX time)
