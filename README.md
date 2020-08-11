# Movie-Recommendation-System
A complete data science project which recommends movies to users using cosine similarity as well as scrap reviews of given movie from IMDB and predicts wheather its positive or negative


# Problem Statement

The problem here is to recommend movies to users based on its already watched or searched history, also scrap reviews for that particular movie from IMDB and show few of the reviews and mention alongside which one of them are positive and which one of them are negative.

# Plan of Action

The project will be divided into 2 parts:-

First part deals with data preprocessing, creating of proper csv data file and recommending movies to user based on cosine similarity
The second part deals with scrapping of reviews for that particular movie from IMDB and displaying a few of the reviews alongside telling wheather the review given by that particular reviewer is positive or negative, this is basically sentiment analysis using Natural Language Processing (NLP).

#Dataset

The dataset is taken from Kaggle, Wikepedia and IMDB from below mentioned links.

https://www.kaggle.com/carolzhangdcimdb-5000-movie-dataset
https://www.kaggle.com/rounakbanik/the-movies-dataset
https://www.kaggle.com/rounakbanik/the-movies-dataset?select=ratings_small.csv
https://en.wikipedia.org/wiki/List_of_American_films_of_2018
https://en.wikipedia.org/wiki/List_of_American_films_of_2019
https://en.wikipedia.org/wiki/List_of_American_films_of_2020

# How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

# Preprocessing Data

The data is not well managed and we had to do a lot preprocessing and then convert it to proper csv file before being used for recommendation.

# Files in order

* Preprocessing_1.ipynb
* Preprocessing_2.ipynb
* Movie_Recommendation.ipynb
* Review_Analysis.ipynb
* Predicting_Reviews.ipynb

# Conclusion

The model performed quite well in recommended movies for a given movie with cosine similarity as well as for predicting reviews the NLP Deep Learning LSTM model gave accuracy around 88% which is also great.
All in all , the project is a success.
