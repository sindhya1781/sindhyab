---
layout: post
title:  Customer Viewership Segmentation of OTT Content
date:   2021-12-01 15:01:35 +0300
image:  06.jpg
tags:   Clustering
---
The critical aspect to digest with a pinch of salt is that the consumer's attention span with respect to any digital content is at most 15 to 30 seconds. The idea is captivate the consumer within that time frame or you've lost them. This project was created to be able to provide the right recommendations to increase viewership across previously unseen shows/movies on netflix.

The goal here was to be able to take in a few movies that a user has seen and provide a list of recommended movies that the user would enjoy based on his/her viewership behavior. This repository contains code written in R containing clusters created based on movies and shows to understand how they related to each other in terms of their ratings and their popularity. Steps followed for this project were as given below -

Processing (ETL)
The first step executed in the plan - imported the data and ensured that the data was tidy for analysis. Multiple columns were available and not all the columns were useful.The following ETL steps based on challenges were performed -

a. Score/Rating column added - IMDB Rating (Scale of 1-10) and Rotten Tomatoes Rating (Scale of 1-100) combined and scaled to rid data of NULL values b. Removal of Metacritic Score, Awards Nominated for & Awards Received c. One hot encoding was used for categorical variables in the data

Visualization (EDA)
The data was then analyzed to understand overall distribution of the data and relationships between different variables

Dimension Reduction
a. Principal Component Analysis (For linear relationships) - with indepth analysis of Scree plots produced b. t-Distributed Stochastic Neighbourhood Embedding (For non-linear relationships) - using different Perplexity scores

Clustering Techniques
The following clustering techniques were tried and compared for the project - 
a. Hierarchical Clustering 
b. k-Means Clustering

| Code is available to be viewed on Github on request |
