# Banking Threat Detection System
This repo focuses on detecting fraudulent transactions using unsupervised machine learning techniques. 
Analysed 2,500 real-world bank transactions.
Implemented the following unsupervised learning algorithms:
1) K-Means Clustering: Fast, scalable to large datasets, works well for spherical and well-separated clusters.
2) Z-Score Analysis: Is a simple statistical method for outlier detection. Works best with normally distributed data.
3) Isolation Forests: Efficient for large datasets. Works well with high-dimensional data.
4) DBSCAN Analysis: Does not require a predefined cluster count. Detects clusters of arbitrary shape. Is robust to noise and outliers and is effective for fraud/anomaly detection. 

The output of each of these algorithms were consolidated and the threat level was calculated. Transactions that have threat level of greater than or equal to 3, are flagged as a potential fraud.

### Outputs:
The outputs of each of these learning algorithms are stored in seperate csv files in the output_folder.
'potential_frauds.csv' stores the list of transactions flagged as fraudulent


