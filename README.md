The objective is to explore and segment a retail customer dataset using unsupervised machine learning techniques, specifically k-means clustering. Unlike supervised learning, this approach focuses on discovering hidden patterns in unlabeled data.

🔍 Project Overview
The project involves the following key steps:

Data Cleaning and Preprocessing

Loading a large retail dataset into a pandas DataFrame

Handling missing values and ensuring correct data types

Filtering data to include only transactions from 2011

Feature engineering: creating new fields like Amount, Date, and Time

Feature Aggregation

Aggregating data by CustomerID to calculate:

Recency (time since last purchase)

Frequency (number of purchases)

Monetary Value (total amount spent)

Minimum, Maximum, and Mean transaction amounts

Outlier Detection and Removal

Using the Interquartile Range (IQR) method to detect and remove outliers in Frequency and Amount

Clustering with K-Means

Creating k-means clustering models with k ranging from 2 to 30

Selecting optimal cluster counts using an elbow plot

Evaluating cluster quality using silhouette scores and plots

📈 Objectives
Apply unsupervised learning techniques to real-world retail data

Understand the importance of data preprocessing in clustering

Explore how different features impact customer segmentation

Determine an optimal number of clusters for meaningful segmentation

📂 Files
customer_segmentation.ipynb: Jupyter Notebook with the full code and analysis

data/: Folder containing the original dataset

plots/: Contains generated elbow and silhouette plots for cluster evaluation
