# Cryptocurrencies

## Overview of the project
In this project we are going to work with Unsupervised Machine Learning algorithms to create an analysis that will help prepare an investment bank to get into the cryptocurrency market.

Our goal is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The steps to apply unsupervised machine learning are the following:

#### 1. Preprocessing the Data for PCA
In this step we are cleaning the dataset to create a dataframe that stores all cryptocurrency names.


#### 2. Reducing Data Dimensions Using PCA 
In this second step we apply the Principal Component Analysis (PCA) algorithm to reduce dimensions of the dataframe.


#### 3.  Clustering Cryptocurrencies Using K-means
In this step we create a K-means algorithm to predict the K clusters for the cryptocurrencies’ data. Based on our finding the number of clusters for K is equal to 4. 

![Elbow.png](https://github.com/ARobles127/Cryptocurrencies/blob/main/Images/Elbow.png)  


#### 4. Visualizing Cryptocurrencies Results
In this step we are creating scatter plots to visualize the distinct groups that correspond to the three principal components,  as well as a table with all the currently tradable cryptocurrencies. 


![3D.png](https://github.com/ARobles127/Cryptocurrencies/blob/main/Images/3D.png) 

This 3D scatter plot  helps us visualize the components and identified and potential outliers. Cluster 2 could be considered as an outlier.



![Crypto_Table.png](https://github.com/ARobles127/Cryptocurrencies/blob/main/Images/Crypto_Table.png) 

In the image above we created a table with tradable cryptocurrencies, highlighting the cryptocurrency that belongs to cluster 2, which is the outlier found on the 3D plot.
  


![Scatter.png](https://github.com/ARobles127/Cryptocurrencies/blob/main/Images/Scatter.png) 

Finally a scatter plot that helps visualize better each cluster. With this plot we clearly see the location of each cluster and we confirm that  cluster 2 is an outlier.  

