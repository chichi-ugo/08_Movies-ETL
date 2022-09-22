# Movies-ETL
Creating clean datasets from web-scraped movie data

## Purpose
In this project, our goal was to extract data from different web sources using Python, clean the data and transform the data using Pandas, and finally load the data with PostgreSQL - in summation, we aimed to create an ETL pipeline of raw movie data scraped from the web to an SQL database that can then be used by hackathon participants to develop algorithms for movie success predictions.

## Results
In the project files, it can be seen that data was extracted from Wikipedia as a JSON file, as well as from Kaggle as a csv files. This data was then cleaned - removing duplicate and excess rows, changing collumn names for clarity, converting the data types where necessary, and parsing the data using regular expressions (Regex) and lambda functions - before being merged. From here, the data was then loaded into an SQL database. Below depicts the resulting queries to confirm that the data was successfully loaded.

### Movies Query
![Movies query](https://github.com/chichi-ugo/08_Movies-ETL/blob/main/Resources/movies_query.PNG?raw=true)

### Ratings Query
![Ratings query](https://github.com/chichi-ugo/08_Movies-ETL/blob/main/Resources/ratings_query.PNG?raw=true)
