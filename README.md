# Neighboorhood Segmentation using KMeans clustering.

This Dataset required intense feature engineering. This dataset has geolocation feature (areas in banglore), rather than making dummy variable I had tried to find the exact co-ordinates of the location using GEOPY library which I call Geo-Feature method and performed Kmeans clustering to group areas near by.
With this technique the error got drastically reduced. To get better understanding of the project please refer to PPT attached in the same repository.

Steps involved :- 

1) Perform Feature Engineering - Taking care of missing values, conveting categorical data etc.
2) Perform Geo-Feature Method to convert geo-location feature in the dataset into numerical.
3) Train the model using Linear Regression Algorithm.
4) Finally compare the results.
