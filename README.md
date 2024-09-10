# Crypto Clustering Analysis

### Project Overview
This project involves clustering cryptocurrencies to understand their market behavior using K-Means clustering and Principal Component Analysis (PCA). The goal is to identify patterns and groupings among cryptocurrencies based on their market data.

### Analysis Goals
Normalize the cryptocurrency market data for clustering.
Determine the optimal number of clusters using the Elbow method.
Cluster cryptocurrencies using K-Means clustering.
Optimize clustering results with PCA and compare the performance.
Visualize the clustering results and analyze the impact of dimensionality reduction.

### Steps
Normalize the cryptocurrency market data for clustering.
Determine the optimal number of clusters using the Elbow method.
Cluster cryptocurrencies using K-Means clustering.
Optimize clustering results with PCA and compare the performance.
Visualize the clustering results and analyze the impact of dimensionality reduction.

### Results
Optimal k value using original data: 4
Optimal k value using PCA data: 4
Total explained variance of PCA components: 89.50%
Impact of using fewer features for clustering: Using fewer features in Principal Component Analysis (PCA) simplifies clustering by decreasing noise and focusing on the most meaningful data patterns. More distinct and well-defined clusters may result from this. But occasionally, important data could be lost during the dimensionality reduction, which could have an impact on how accurate the clusters are. Although the visual separation of clusters created by PCA may be greater, the underlying data's granularity may be diminished. So, while some data specificity may be lost, employing fewer characteristics might help make the cluster definition more clear.

### Credits
Data Source: crypto_market_data.csv, Xpert Learning Assistant
Libraries Used: Pandas, scikit-learn, hvPlot, Matplotlib

