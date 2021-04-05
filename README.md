# Week 10 Project:

## Movie Recommender System

This project was completed in week 10 of the Data Science Bootcamp at Spiced Academy in Berlin, together with [Pietro Passarella](https://github.com/PIETRO-ing).

We built a movie recommender with a web interface utilizing the [small movielens dataset](https://grouplens.org/datasets/movielens/), which includes a collection of 9742 movies previously rated by 610 users.

The aim of the project was to explore and utilize the ```surprise``` library. The current version is not exactly the most efficient and practical application since it takes the algorithm ~45-60 seconds to make its recommendation. Still,  ```surprise```'s [famous SVD algorithm](https://surprise.readthedocs.io/en/stable/matrix_factorization.html#surprise.prediction_algorithms.matrix_factorization.SVD) is super powerful and is worth checking out.

All EDA files are in the [EDA](EDA) folder. All files for the web-app are in the [flask](flask) folder.

## How to use

* Clone the repo
* Make sure you have the [required libraries](requirements.txt).
* Go to the flask directory in a terminal and run `python application.py` and follow the link to  http://127.0.0.1:5000/

## TO-DO
* Improve the bulky function
* Add ```scikit-learn``` alternative
* Deploy with Heroku