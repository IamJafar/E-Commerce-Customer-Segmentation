# E-Commerce-Customer-Segmentation

## Abstract
  A key challenge for e-commerce businesses is to analyze the trend in the
market to increase their sales. The trend can be easily observed if the
companies can group the customers; based on their activity on the ecommerce site. This grouping can be done by applying different criteria like
previous orders, mostly searched brands and so on. 

## Problem Statement
  Given the e-commerce data, use k-means clustering algorithm to cluster
customers with similar interest. 

## Dataset Information

| Column | Description                            |
|--------|----------------------------------------|
| Cust_ID| Unique Numbering of Customers          |
| Gender | Gender of Customer                     |
| Orders | No. of Past orders placed by the customers    |
---------------------------------------------------
Remaining 35 features (brands) contains the number of times
customers have searched them.


## Work Flow

- First Import the necessary libraries needed for the project. Below are the libraries that I have used
    - import pandas as pd
    - import numpy as np
    - import matplotlib.pyplot as plt
    - import seaborn as sns
    - from sklearn.preprocessing import MinMaxScaler
    - from sklearn.metrics import silhouette_score
    - from sklearn.cluster import KMeans
    - from yellowbrick.cluster import KElbowVisualizer
- Load the dataset using pandas.
- Perform the data cleaning techniques like treating the missing values.
- Visualize the data with the help of Matplotlib or Seaborn to get better understanding of the features.
- Perform the data scaling using minmaxscaler and data will be scaled between 0 and 1.
- Implement the Elbow method or Silhouette method to find the optimum number of K. Also visualize them with plots.
- After getting optimum K value use it as number of clusters and perform the model fit.
- The model will provide the output with different clusters.
- Analyze each clusters to find the similarities.
- Finally get the conclusion by analyzing each clusters.

