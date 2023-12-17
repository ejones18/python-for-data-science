# Python for Data Science - Week 3 Capstone project : Initial reading

This week's homework / capstone project will task you with creating a clustering classification model on the iris dataset that we explored last week. Please work through the first notebook of this week's homework for a step-by-step example of doing this on another dataset.

This file will explore a handful of topics that will be introduced in this week's homework. Please take some time to look over the content of this file as it will be a huge help when working through the notebooks. There is also a wiki file that contains a brief description of all the functions used in the homework notebook to help you further understand. Good luck!

## Principal component analysis (PCA)

Principal component analysis (PCA) is a dimensionality reduction technique used to transform high-dimensional data into a lower-dimensional space. It aims to find the directions (principal components) along which the data varies the most. By projecting the data onto these principal components, we can reduce the dimensionality of the data while preserving most of its variance.

_Note: This is an extension topic that you could choose to include in your project should you wish to challenge yourself._

## K-means clustering

K-means clustering is an unsupervised machine learning algorithm used to partition a dataset into K clusters. It aims to minimise the sum of squared distances between the data points and their respective cluster centroids. The algorithm iteratively assigns data points to the nearest centroid and updates the centroids until convergence. 

When applying K-means clustering, it is important to explore and select the appropriate features from the dataset. The choice of features can greatly impact the clustering results. It is recommended to analyse the dataset and consider features that are relevant and meaningful for the clustering task. This can be done by examining the data distribution and correlation between features. 

When selecting features for clustering, it is important to look for the following characteristics:

1. Relevance: Choose features that are likely to have a significant impact on the clustering results - features that have high variability and distinguishable patterns among data points are usually more relevant.

2. Discriminative power: Look for features that can effectively differentiate between different clusters.

## Elbow method for determining the number of clusters

The elbow method is a technique used to determine the optimal number of clusters in K-means clustering. It involves plotting the within-cluster sum of squared distances (WCSS) against the number of clusters. The WCSS measures the compactness of the clusters, and the elbow point on the plot represents the number of clusters where the rate of decrease in WCSS starts to level off. This point is often considered as the optimal number of clusters.

## Silhouette score metric

The silhouette score is a metric used to evaluate the quality of clustering results. It measures how well each data point fits into its assigned cluster compared to other clusters. The silhouette score ranges from -1 to 1, where a score close to 1 indicates that the data point is well-clustered, a score close to 0 indicates that the data point is on or very close to the decision boundary between two clusters, and a score close to -1 indicates that the data point may have been assigned to the wrong cluster.

## Supporting material

- [Introduction to Principal Component Analysis](https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c)
- [Understanding PCA](https://builtin.com/data-science/step-step-explanation-principal-component-analysis)
- [Introduction to K-means Clustering](https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1)
- [K-means Clustering in Python](https://realpython.com/k-means-clustering-python/)
- [Elbow Method for Determining the Number of Clusters](https://towardsdatascience.com/machine-learning-algorithms-part-9-k-means-example-in-python-f2ad05ed5203)
- [Elbow Method for Optimal Clustering](https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/)
- [Understanding Silhouette Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html)
- [Silhouette Analysis in Python](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)
- [Introduction to using Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-ml/)
- [Introduction to using Azure Machine Learning 2](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-azure-ml-in-a-day?view=azureml-api-2)

Note: The following links essentially cover what is asked of you in this week's homework... only use if you're very stuck!

- [K-means clustering for Iris dataset](https://www.kaggle.com/code/khotijahs1/k-means-clustering-of-iris-dataset)
- [K-means clustering for Iris dataset 2](https://medium.com/analytics-vidhya/clustering-on-iris-dataset-in-python-using-k-means-4735b181affe)