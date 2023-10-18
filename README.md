# Coinmarket_phase2
## question 1 
#### Part 1: K-Means Clustering
In the first part of the analysis, we applied the K-Means clustering algorithm using only two features, cap market, and volume, to cluster the dataset into 5 clusters. We then plotted the results on a scatter plot, highlighting which data points belong to each cluster. The center of each cluster is also marked on the plot.
#### Part 2: Choosing the Optimal K
In the next step, we executed the K-Means algorithm for values of k ranging from 1 to 10. To determine the optimal value for k, we calculated the Sum of Squares Within Clusters (Square of Sum Cluster-Within). Selecting the appropriate k value is crucial, and we put effort into finding the most suitable one. We use Elbow Method but this choice is ambiguous. We could choose k to be either 3 or 4. In such an ambiguous case, we may use the Silhouette Method. The optimal k value of 4 was chosen and the modeling was done with 4
#### Part 3: DBScan Clustering
In the final part of the analysis, we used the DBScan clustering algorithm to cluster data points based on cap market and volume. We adjusted hyperparameters to create 5 meaningful clusters. 
Clustering result of K = 5  with DBSCAN:
•	Cluster -1 contains 10 data points, which is approximately 1.22% of the total.
•	Cluster 0 contains 169 data points, which is approximately 20.73% of the total.
•	Cluster 1 contains 129 data points, which is approximately 15.85% of the total.
•	Cluster 2 contains 725 data points, which is approximately 88.94% of the total.
•	Cluster 3 contains 363 data points, which is approximately 44.58% of the total.
•	Cluster 4 contains 60 data points, which is approximately 7.37% of the total.

## question 2



## question 3




## Getting Started
Clone this repository:
git clone https://github.com/iliyapr/coinmarket_phase2.git
Refer to the Jupyter Notebook or code files to replicate the analysis and explore the results.


## Conclusion

This project provides insights into the cryptocurrency market 
