# Movie recommendation
 
 A simple implementation of a Movie recommendation system using collaborative filtering

## Goal of the project

The objective of collaborative filtering is to predict movie ratings for the movies that users have not yet rated.
This will allow us to recommend the movies with the highest predicted ratings to the user.


## Data set

The matrix Y (a num movies × num users matrix) stores the ratings y(i,j) (from 1 to 5).
The matrix R is an binary-valued indicator matrix, where R(i, j) = 1 if user j gave a rating to movie i, and R(i, j) = 0 otherwise.


## Get tour own movie recommendations

You can enter your own movie preferences, so that later when the algorithm runs, you can get your own movie recommendations!
Some movies have been ranked based as an example on how to do it, but you should change this according to your own tastes.

To update your preferences, edit `code\movie_recommender.m`, line 22, add a line
```matlab
my_ratings(movie_idx) = 3;
```
Where ``movie_idx`` is the index of the movie you want to rate 3/5.
The list of all movies and their number in the dataset can be found listed in the file `data\movie_ids.txt`

Then, to get your recommendations, simply run the script `code\movie_recommender.m`, the recommendations
are outputted in the console.

## Note

This project was part of [Andrew Ng's Mooc on machine learning](https://www.coursera.org/learn/machine-learning) which I strongly recommend.


This project is no longer updated.