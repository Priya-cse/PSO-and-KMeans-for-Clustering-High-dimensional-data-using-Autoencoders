# Enhancing the Performance of the PSO Algorithm for Clustering High dimensional data using Autoencoders

_**Abstract**_

The emergence of big data has brought new challenges in processing and analyzing large and complex datasets due to their high dimensionality. Unsupervised learning techniques like clustering have become powerful tools for identifying patterns and relationships in data without the need for labeled examples. One popular Unsupervised data clustering technique is K-means and Particle Swarm Optimization(PSO). Using K-means clustering with optimization can lead to better clustering results by combining the strengths of both algorithms. To automate the data clustering, the Elbow method is implemented, which provides the K value for implementing K-means and PSO. Clustering high-dimensional data can be challenging due to the curse of dimensionality, where the number of dimensions dramatically outnumbers the number of data points. Therefore, a dimensionality reduction technique must be employed to enhance the performance of clustering high-dimensional data. Thus, we used Autoencoder as one of the dimensionality reduction techniques with K-means and PSO clustering and compared the clustering performance on reduced and original data

_**Objectives**_
1. Design and develop a PSO algorithm for automatic data clustering.
2. Design and develop PSO employing Autoencoder for data clustering.
3. Compare the performance of PSO and Autoencoder-based PSO data clustering algorithms using different validity indices.
4. Apply this algorithm to Stock Market Data and obtain inferences.

_**Methodology**_

![methodology](https://github.com/Priya-cse/PSO-and-KMeans-for-Clustering-High-dimensional-data-using-Autoencoders/assets/89922343/047ef794-875a-4a52-9255-6e371314021d)

_**Results**_

| Method | K-Means PSO     | K-Means PSO with Autoencoders |
| -------- | --------------------- | --------------------- |
| Dataset  | DB Index&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Silhouette Index| DB Index&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Silhouette Index|
| High     | 0.99316&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.044056| 0.499879&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.598376|
| Low      | 0.98635&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.079333| 0.492837&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.694484|
| Close    | 0.98474&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.046373| 0.474543&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.634368|
| Open     | 0.93643&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.056383| 0.547732&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.745483|
| Volume   | 0.99736&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.043367| 0.498746&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0.648464|

_**Conclusion**_

Based on the evaluation metrics, used to measure the quality of clustering such as DB-index and Silhouette index, the PSO and K-means algorithm with autoencoders outperformed compared to PSO and K-means without autoencoders.​
		
		
		
