# data-sci-DBSCAN



Hello, 

The purpose of this repository is for resume purposes, to display the previous work i have completed in the domain of data science 
by way of my courses. Please see the html and pdf files for ease of view if you do not have access to a virtual environment like 
jupyter notebook or google colab that views python notebook files (.ipynb).

This project was to show the pros and cons between KMEANS and DBSCAN (Density-Based Spatial Clustering of Applications with Noise).

K-Means clustering may cluster loosely related observations together. Every observation becomes a part of some cluster eventually, even if the observations are scattered far away in the vector space. Since clusters depend on the mean value of cluster elements, each data point plays a role in forming the clusters. A slight change in data points might affect the clustering outcome. This problem is greatly reduced in DBSCAN due to the way clusters are formed. This is usually not a big problem unless we come across some odd shape data.

Another challenge with k-means is that you need to specify the number of clusters (“k”) in order to use it. Most of the time, we won’t know what a reasonable k value is from the start.

What’s nice about DBSCAN is that you don’t have to specify the number of clusters to use it. All you need is a function to calculate the distance between values and some guidance for what amount of distance is considered “close”. DBSCAN also produces more reasonable results than k-means across a variety of different distributions. 

Best, Eugenia. 
