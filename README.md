#  Customer Segmentation using RFM Analysis & Clustering

This project performs customer segmentation on retail transaction data using RFM (Recency, Frequency, Monetary) analysis with K-Means clustering to identify distinct customer behavior patterns. Transaction-level data was transformed into customer-level behavioral profiles through feature engineering and aggregation, followed by clustering to uncover meaningful customer groups.

The optimal number of clusters was determined using the Elbow Method and validated using Silhouette Score analysis. The final model achieved strong cluster separation and identified multiple customer segments ranging from inactive users to elite high-value customers.

##  Customer Segmentation Summary

| Cluster | Segment | Avg Recency | Avg Frequency | Avg Monetary | Customers | Business Insight |
|---|---|---|---|---|---|---|
| 4 | Elite Premium Customers | 7.67 | 42.83 | 190863.46 | 6 | High-value VIP customers |
| 2 | High-Frequency VIPs | 1.50 | 135.83 | 58381.12 | 6 | Bulk buyers with extreme purchase frequency |
| 3 | Active Customers | 15.72 | 22.30 | 13534.00 | 203 | Highly engaged repeat customers |
| 0 | Regular Customers | 43.81 | 3.69 | 1358.77 | 3060 | Occasional customers |
| 1 | Churned Customers | 248.47 | 1.55 | 480.42 | 1063 | Inactive users |
