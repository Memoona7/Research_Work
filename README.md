# Research_work
# Research_work
In this project, it selects relevant text features using Evolutionary Algorithm, and classifies the fake reviews from genuine reviews.
This project can be seen by simply opening in Google Colab.

Labelled dataset is taken from Kaggle, consists of 40000 plus text reviews and from different 10 categories of product domains to prove diversity of model.
Dataset link is available: https://www.kaggle.com/datasets/mexwell/fake-reviews-dataset

In project: First, Dataset is loaded from Google Drive.
Dataset is the preprocessed by a number of steps.
Dataset is showed visually, first graph to show the ratings of reviews, then graph of count of fake and genuine reviews which were both type of reviews were equal, top frequencies of words and word cloud.
Then without using feature selection, used CNN to classify reviews but there was a huge overfitting of data.
Then Self-organizing Genetic Cooperative Optimization algorithm is used to select relevant text features, overfitting was less, by overcoming more overfitting and used CNN to classify there was an accuracy of 93%.
Ant Colony Optimization algorithm is used to compare the performance, there was 72% accuracy with overfitting of data as well.

Project is created using Google Colab, mainly resources used from Colab are high Ram and GPU accelerator.
