# Python-TMDB
> This project is inpired by [Kaggle](https://www.kaggle.com/datasets/sankha1998/tmdb-top-10000-popular-movies-dataset/data). Please visit the link for further information.

> Please consider visiting these works by [Rbgd](https://www.kaggle.com/code/rihaab04/basic-recommendation) and [Saishiyam](https://www.kaggle.com/code/saishiyam/movie-recommendation-system). They are amazing. 

## Scenario 
TMDB.org is a crowd-sourced movie information database used by many film-related consoles, sites and apps, such as XBMC, MythTV and Plex. Dozens of media managers, mobile apps and social sites make use of its API.
TMDb lists some 80,000 films at time of writing, which is considerably fewer than IMDb. While not as complete as IMDb, it holds extensive information for most popular/Hollywood films.
This is dataset of the 10,000 most popular movies across the world has been fetched through the read API.
TMDB's free API provides for developers and their team to programmatically fetch and use TMDb's data.
Their API is to use as long as you attribute TMDb as the source of the data and/or images. Also, they update their API from time to time.

This data set is fetched using exception handling process so the data set contains some null values as there are missing fields in the tmdb database.

P.S: In the overview section, there are 30 missing data. In this Analysis, we will remove those data. 

## Implementation
* `Import libraries`: pandas, numpy, matplotlib.pyplot, seaborn.
* `Load dataset`: Load the dataset and check the dataset.
* `Drop the missing row`: There are 30 data in overview column.
* `Check the missing values once again`: Investigate the missing values after dropping 30 data.
* `Which language has the most number of movies`: English language has the most number of movies.
  ![English - Most Number of Movies](https://github.com/Kwangsa19/Python-TMDB/assets/135963482/61270ab4-85d3-4138-ae1f-0eed63c10c13)

* `Distribution of vote average`: The distribution is between 4.0 and 8.0.
  ![Distribution - Vote - Average](https://github.com/Kwangsa19/Python-TMDB/assets/135963482/87790671-72a7-405c-99b4-0dab8452e588)

* `Top 10 movies with the most number of votes`: Inception, Deadpool, and the Avengers topped the chart.
  ![Top 10 Movies - Most Number of Votes](https://github.com/Kwangsa19/Python-TMDB/assets/135963482/371c2b5b-d1d4-4a2c-b979-a597ea5e0989)

* `Weighted average formula from IMDB`: The shawshank Redmeption, the Godfather, and Pulp Fiction topped the chart.
  ![Top 10 Movies - Weighted Average Formula (Based on IMDB)](https://github.com/Kwangsa19/Python-TMDB/assets/135963482/c6c848a8-9460-48df-93a8-67d625fa0b64)

## Future Works
* To find the similar movies based on its respective overview, pleave visit this [link](https://github.com/Kwangsa19/Python-TMDB-Movie-Recommendation). 
