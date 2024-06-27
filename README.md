# Customer Segmentation Using K-Means Clustering

## Overview

This project segments customers based on their annual income and spending score using the K-Means clustering algorithm. This helps in understanding customer groups for targeted marketing.

## Dataset

The dataset includes:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Workflow

1. Data Exploration:
   - Load the dataset and inspect its structure.
   - Check the number of rows and columns, null values, and summary statistics.

2. Feature Selection:
   - Use 'Annual Income' and 'Spending Score' for clustering.

3. Determine Optimal Clusters:
   - Use the Elbow Method with K-Means for 1 to 10 clusters.
   - Plot WCSS vs. number of clusters to find the elbow point indicating the optimal number of clusters.

4. K-Means Clustering:
   - Apply K-Means with the optimal number of clusters.
   - Fit the model and predict cluster labels.

5. Visualization:
   - Scatter plot of customer segments with different colors.
   - Plot centroids of clusters.

## Results

The results show distinct customer groups based on annual income and spending score. These insights can be used for targeted marketing and personalized offers.

## Conclusion

K-Means clustering provides valuable insights into customer segmentation, aiding effective business strategies.

