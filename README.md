# UCB-ELT-Project

In this project I created automated pipeline to extracted, transformed, and loaded data from Wikipedia and Kaggle. Once the data is cleaned, the Wikipedia and Kaggle Movies datasets are merged into one dataset. The ratings dataset is kept apart. The newly transformed datasets are then loaded into SQL database for further analysis.

Steps followed:
- The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.
- Filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.
- consolidated the redundant data, removed the duplicates, formatted and grouped the data.
- The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
- Load the data to a PostgreSQL Movie Database

Summary
The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used for analysis.

