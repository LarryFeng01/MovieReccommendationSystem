# MovieReccommendationSystem
### Larry Feng

The reccommendation system is an important part of our lives, even through many people don't realize the name of the concept. Many applications use a reccommendation system to provide you with products or advertisements that fit your taste so you keep using the service or are more likely to buy something from an ad. For example, once you watch some movies on Netflix and submit your ratings, the service will take your movie tastes into account, and, based on other users' data, reccommends you more movies to watch. The general idea is simple: if many people watched movie x and enjoyed it but also enjoyed movie y, if you enjoy movie x, the system might reccommend you movie y. Although there are a few different ways to make a reccommendation system, I plan to use the movie descriptions on imdb and ratings to make an accurate system using NLP.

In this project, I hope to gain some insight on how large companies use their reccommendation systems to gain profits and how I can turn my natural language processing programming into a marketable skill.

TODO:
- Research: Understand what kind of reccommendation system I'm looking for- Demographic Filtering, Content Based Filtering, or Collaborative Filtering.
- Data: Find a dataset that contains movie descriptions and ratings
  - Potential Problem: Dataset is not large enough, Data is not cleaned, 
  - Find data that I can work with (able to run with my GPU)
  
  

March 13 Update:
Dataset Creation

1. a) The data used will be from kaggle.
   b) The data will be downloaded through csv files.
   c) The license is CC0: Public Domain.
   d) [https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv).
   
2. a) The main dataset with movie descriptions contains 45,000 movies with 24 attributes(budget, genres, revenue, etc.). A second dataset contains 26 million ratings from 270,000 users for all movies.
   b) The datasets are in csv format.
   c) The datasets are in dataframes.
   
3. a) No data models are used.
   b) Lists and dictionaries are used in the dataset.
