# MovieLens: Harvard edX Data Science Capstone Project
![Header](https://github.com/xavier-lim/movieLens/blob/main/images/movieLens_header.jpg)

As part of Harvard's edX Data Science Course Capstone Project, I created a model to predict user ratings of movies, similar to Netflix's movie recommendation system. These predictions are made using average movie ratings and average user ratings. Ultimately, this type of analysis can be utilized to make tailored consumer recommendations which could increase revenue and improve customer retention.

## Table of Contents
1.	[Project Tools](https://github.com/xavier-lim/movieLens#project-tools)
2.	[Data Source](https://github.com/xavier-lim/movieLens#data-source)
3.	[Results](https://github.com/xavier-lim/movieLens#results)
4.	[Conclusion](https://github.com/xavier-lim/movieLens#conclusion)
5.	[Author](https://github.com/xavier-lim/movieLens#author)

## Project Tools
*	R
*	R Studio - [RStudio Desktop](https://rstudio.com/products/rstudio/download/)
*	MovieLens Dataset (10M Version)

## Data Source
All the data for this project was collected from [GroupLens](https://grouplens.org/datasets/movielens/10m/). The dataset presents information about **10 million** movie ratings including user id, movie id, user rating of the movie, timestamp of the rating, title of the movie, and movie genre(s).

## Results

Model                        | RMSE
---------------------------- | -------
Model 1: Movie Effect        | 0.9423
Model 2: User Effect         | 0.9700
Model 3: Movie & User Effect | 0.8768

## Conclusion
In conclusion, taking into account user preferences and a movie’s average rating does a better job of predicting ratings than simply taking into account only user effects or only movie effects.


## Author
* **Xavier Lim** - [LinkedIn](https://www.linkedin.com/in/xavier-lim14/)  |  [Portfolio Website](https://xavier-lim.github.io/)  |  [Tableau Public](https://public.tableau.com/profile/xavier.lim#!/)
