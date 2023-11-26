# FoDS Week 9 Forum
## Dataset Used: Wine Dataset

### 1. K-Means Clustering
K-Means is a partitioning method that aims to partition n observations into k clusters. The algorithm iteratively assigns each data point to one of k clusters based on the mean of the data points.
Result:

Silhouette Score: 0.5711220218931753

Davies-Bouldin Index: 0.534266070367968

Rand Score: 0.37111371823084754

Calinski and Harabasz Score: 561.805170619475

The results suggest that the K-Means algorithm has identified clusters in the data, with moderately well-defined and separated clusters. However, the Rand Score indicates that the agreement with the true labels is not very high, and there may be some misclassification or overlap between clusters.

### 2. Means Shift Clustering
Mean Shift is a non-parametric clustering algorithm used for identifying dense regions in a dataset. 
Result:

Silhouette Score: 0.5024822932496186

Davies-Bouldin Index: 0.5561815764333428

Rand Score: 0.39723664098601413

Calinski and Harabasz Score: 454.0526193288132

Mean Shift has produced clusters with a moderate level of cohesion and separation, as indicated by the Silhouette Score. The Davies-Bouldin Index and Calinski and Harabasz Score suggest that the clusters are reasonably well-separated and distinct. The Rand Score indicates a moderate level of agreement with the true labels.

### 3. Agglomerative Clustering
Agglomerative Clustering is a hierarchical, bottom-up clustering algorithm used for grouping similar data points into progressively larger clusters.
Result:

Silhouette Score: 0.5644632902637768

Davies-Bouldin Index: 0.5357594721642328

Rand Score: 0.36840191587483156

Calinski and Harabasz Score: 552.8413535988415

Agglomerative Clustering has produced clusters with a reasonable level of cohesion and separation, as indicated by the Silhouette Score. The Davies-Bouldin Index and Calinski and Harabasz Score suggest that the clusters are reasonably well-separated and distinct. The Rand Score indicates a moderate level of agreement with the true labels.

### 4. Spectral Clustering
Spectral Clustering is a technique for clustering data points based on the eigenvectors of a similarity matrix derived from the data. 
Result:

Silhouette Score: 0.28034429912294523

Davies-Bouldin Index: 0.44772786748913673

Rand Score: 0.000351000351000351

Calinski and Harabasz Score: 3.36909099369962

Spectral Clustering has produced clusters with a lower level of cohesion and separation, as indicated by the Silhouette Score. The Davies-Bouldin Index suggests that the clusters are reasonably well-separated, but the Rand Score and Calinski and Harabasz Score indicate a lower level of agreement with the true labels and a lower level of cluster separation.

