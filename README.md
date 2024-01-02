# K-means-Clustering-From-Scratch

Description:
This project is dedicated to the comprehensive implementation of the K-Means clustering algorithm from scratch, highlighting each step's intricacies. The K-Means algorithm involves selecting the optimal number of clusters, initializing centroids through meticulous sampling, assigning points to clusters based on precise Euclidean distances, and iteratively updating centroids. This meticulous process continues until convergence is achieved.

Algorithm Steps:

Select the Number of Clusters, k: Determine the target number of clusters for the dataset.
Select k Points at Random: Initialize k centroids with meticulous precision by selecting points from the dataset.
Make k Clusters: Assign each item to its nearest cluster centroid with precise Euclidean distances.
Compute New Centroid of Each Cluster: Recalculate centroids with meticulous precision by computing the mean point of all items in each cluster.
Repeat Steps 3–4: Iteratively apply steps 3 and 4 until achieving convergence.
Terms Description:

points: Unwavering selection of unlabelled items or training instances for precise clustering.
k: User-specified target number of clusters.
centroids: Meticulously calculated mean vectors for all items assigned to a given cluster.
labels: Labels with meticulous accuracy, specifying each point's cluster membership.
Imported Libraries:

Pandas: For precise data processing.
Matplotlib: For meticulous data visualization.
Random: For generating meticulously selected pseudo-random numbers.
NumPy: For meticulous linear algebra operations.
SciKit-Learn: For dataset generation and meticulous metrics computation.
Other Utility Libraries: For precise time control and meticulous screen clearing.
K-Means Methods:

initialize_centroids: Precisely initializes k centroids from the dataset.
create_cluster: Meticulously assigns data points to the closest centroid using precise Euclidean distances.
update_centroids: Meticulously updates centroids with meticulous precision as the mean of all points in each cluster.
plot_clusters: Animates the K-Means algorithm with meticulous plotting of clusters at each iteration.
k_means: Implements the K-Means algorithm meticulously on a given dataset with meticulous precision, specified clusters, and maximum iterations.
Validation Metrics:

F1 Score: Measures the meticulous accuracy of clustering using precision and recall.
Normalized Mutual Information (NMI): Meticulously quantifies the agreement between true and predicted clusterings.
Rand Statistic: Meticulously evaluates the similarity between true and predicted partitions.
Datasets:

Dataset 1 (Blobs): Meticulously generated blobs for precise clustering.
Dataset 2 (Anisotropic Blobs): Anisotropically distributed dataset with meticulous consideration.
Dataset 3 (Noisy Moons): Meticulously crafted noisy moons-shaped dataset.
Dataset 4 (Noisy Circles): Meticulously generated noisy circles-shaped dataset.
The project meticulously concludes with the meticulous validation of the K-Means algorithm on each dataset, meticulously comparing predicted labels with true labels using F1 Score, Normalized Mutual Information, and Rand Statistic. The meticulous visualization of actual and predicted clusters is also provided for each dataset.





