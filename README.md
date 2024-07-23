# README for Customer Segmentation and Analysis

## Overview

This project aims to segment customers based on their demographic and purchasing behavior using K-Means clustering. By analyzing the segments, businesses can tailor their marketing strategies to target different customer groups more effectively.

## Project Steps

### (1) Imported essential libraries

  Including NumPy, Pandas, Matplotlib, Seaborn, Plotly, and Scikit-learn's KMeans for clustering.
  
### (2) Exploration of Data

  Load the customer dataset, which includes features such as Age, Annual Income, Spending Score, and Gender.

### (3) Data Visualization

  Visualize the distributions of age, annual income, and spending scores through histograms to understand the data better.
  A count plot is used to show the gender distribution.
  Create scatter plots to examine relationships between different pairs of features (e.g., Age vs. Annual Income, Annual Income vs. Spending Score).

### (4) Clustering using K-Means

  Segment the customers using K-Means clustering based on different feature combinations.

### (5) Segmentation using Age and Spending Score
 
  Use Age and Spending Score for clustering. 
  Select an optimal number of clusters by plotting the inertia for different cluster counts.

### (6) Segmentation using Annual Income and Spending Score
  
  Use Annual Income and Spending Score for another clustering analysis.

### (7) Segmentation using Age, Annual Income, and Spending Score

  Perform clustering using all three features (Age, Annual Income, and Spending Score). 
  This gives a more comprehensive view of customer segments.

### (8) 3D Visualization

  For the final clustering analysis, create a 3D scatter plot using Plotly to visualize the clusters based on Age, Annual Income, and Spending Score.

## Results and Interpretation
  
The visualizations and clusters provide insights into different customer groups. For example, younger customers with higher spending scores can be targeted with premium   marketing campaigns, while older customers with lower spending scores might benefit from budget-friendly promotions.
