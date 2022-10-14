# K-Means_DBSCAN

## Cluster the IRIS dataset using both K-means and DBSCAN
Justify the k you choose using silohuette coefficient and the Elbow method:

- The K used in K-Means is the result where the decrease in inertia begins to slow in the elbow curve.
- The K in DBSCAN is the result of the highest value of the silhouette coefficients

How many clusters detect DBSCAN?
- 3

Which parameters did you use for DBSCAN?
- Just the eps and min_samples

Which algorithm better cluster the IRIS dataset and why?

- Both have favorable points, while the silhouette score in K-Means is a little bit lower compared with the socre in DBSCAN, both can detect 3 clusters, the difference is that the noise in DBSCAN detected 8 points that could be considered as outliers.

To run the 3d Graphs just download the code and the libraries that are needed.

This is the image of the 3d graph for k-means:
![K-Means](imgs/k-means.PNG)

This is the image of the 3d graph for DBSCAN:
![DBSCAN](imgs/DBSCAN.PNG)
