# Cryptocurrency Clustering Analysis

This repository contains code for clustering analysis of cryptocurrency market data using K-Means clustering algorithm with and without Principal Component Analysis (PCA).

## Overview

In this project, I explore two approaches to clustering cryptocurrency market data:

1. Clustering using K-Means algorithm on the original data.
2. Clustering using K-Means algorithm on data transformed by Principal Component Analysis (PCA).

## Code Overview
1. clustering_analysis.ipynb: Jupyter Notebook containing the code for clustering analysis.
2. Resources/crypto_market_data.csv: CSV file containing cryptocurrency market data.
   
## Results
### Clustering on Original Data
1. Used K-Means algorithm to cluster the original cryptocurrency market data.
2. Determined the optimal number of clusters using the elbow method and silhouette score.
3. Visualized the clusters using scatter plot.
### Clustering with PCA
1. Conducted Principal Component Analysis (PCA) to reduce the dimensionality of the data.
2. Applied K-Means algorithm to the PCA-transformed data.
3. Evaluated the performance of clustering using silhouette score.
4. Visualized the clusters using scatter plot.
## Conclusion
1. The best value for k in clustering on original data was determined to be k=2, based on silhouette score.
2. PCA was used to reduce the dimensionality of the data and improve clustering performance.
3. Clustering on PCA-transformed data also resulted in k=2 as the best number of clusters.
4. The choice between clustering on the original data and using PCA depends on specific goals and data characteristics.