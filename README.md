# customer-segmentation-in-k-means
k means
## 🚀 Features
Uses K-Means Clustering (Unsupervised Machine Learning)
Custom initial centroids are provided
Displays final cluster assignments
Prints final centroid positions
Generates a cluster visualization plot
Saves output plot as a high-resolution PNG image

## 🛠️ Technologies Used
Python 3.x
NumPy
Matplotlib
Scikit-learn (KMeans)


How K-Means Works(Algo Explanation)

K-Means is an unsupervised learning algorithm that groups data into k clusters.

Steps:
Initialize k centroids (here we provide initial centroids manually)
Assign each point to the nearest centroid using Euclidean Distance
Update centroid positions by taking the mean of all points in the cluster
Repeat until centroids stop changing (convergence)

## The goal is to minimize:

WCSS (Within Cluster Sum of Squares)

𝑆
𝑆
