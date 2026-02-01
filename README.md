# CUSTOMER-SEGMENTATION-USING-KMEANS-CLUSTERING

Project Overview

This project applies K-Means clustering to segment customers based on purchasing behavior. The goal is to identify distinct customer groups that can be targeted with tailored marketing strategies. The objective is to identify distinct customer groups that can be used to inform targeted marketing strategies, improve customer engagement, and optimize business decision-making.

Customer segmentation is an unsupervised learning problem, and K-Means clustering was chosen due to its effectiveness in identifying patterns within numerical data.

## Dataset
The dataset contains customer-level information including:
- Annual Income
- Spending Score

These features capture both purchasing power and behavioral tendencies, making them suitable for segmentation analysis.

## Methodology
The analysis followed a structured machine learning workflow:
1. Data loading and inspection
2. Feature selection for clustering
3. Determination of the optimal number of clusters using the Elbow Method
4. Training the K-Means clustering model
5. Assigning cluster labels to each customer
6. Visualization of clusters and their centroids

 ## Model
- Algorithm: K-Means Clustering
- Initialization: k-means++
- Number of clusters: 5
- Distance metric: Euclidean distance

The model groups customers by minimizing within-cluster variance, resulting in well-separated and interpretable segments.

## Results and Interpretation
The model identified five distinct customer segments with clear differences in income and spending behavior. These clusters represent groups such as high-income high-spending customers, high-income low-spending customers, and low-income segments with varying spending patterns. Each segment provides actionable insights that can be leveraged for targeted marketing, customer retention, and resource allocation strategies.

Cluster centroids highlight the central tendencies of each group and confirm meaningful separation between customer segments.


## Visualization
Customer clusters are visualized using a two-dimensional scatter plot with annual income on the x-axis and spending score on the y-axis. Cluster centroids are highlighted to show the center of each segment.

This visualization helps validate the clustering results and makes the segmentation easily interpretable for both technical and non-technical audiences.


