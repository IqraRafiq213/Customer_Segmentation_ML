The objective is to apply unsupervised learning techniques to real-world retail data by using unsupervised machine learning techniques, specifically k-means clustering. This approach focuses on discovering hidden patterns in unlabeled data and determining an optimal number of clusters for meaningful segmentation. 

Project Description: 
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


