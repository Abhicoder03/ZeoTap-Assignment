# ZeoTap-Assignment

# Customer Segmentation and Clustering Project

## Overview
This project aims to perform customer segmentation using clustering techniques based on profile and transaction data. By grouping customers into distinct clusters, businesses can better understand customer behavior, target specific customer segments, and enhance decision-making.

## Project Workflow
- Data Preparation

Loaded customer data (Customers.csv) and transaction data (Transactions.csv).
Merged datasets to create a comprehensive view of customer profiles and transaction history.

- Feature Engineering

Derived additional features like:
Total Spending: Total value of all transactions by a customer.
Average Transaction Value: Mean value of transactions per customer.
Transaction Count: Number of transactions made by each customer.

- Data Preprocessing

Scaled the features using StandardScaler to ensure uniformity in feature magnitude.

- Clustering

Used DBSCAN (Density-Based Spatial Clustering of Applications with Noise) for clustering.
Selected 4 clusters as the optimal number based on evaluation metrics.

- Evaluation Metrics

Davies-Bouldin Index: 0.7437.
Silhouette Score: 0.4680.

- Visualization

Visualized clusters using scatter plots to observe the separation and distribution of data points.

## Key Results
- Number of Clusters Formed: 4 clusters.
- Davies-Bouldin Index: 0.7437 (indicating compact and well-separated clusters).
- Silhouette Score: 0.4680 (moderate cluster distinctiveness).

##                                                                                    Made with :heart:
