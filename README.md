# DataScienceF9

In my code, I implemented 4 scoring indexes to compare 4 clustering algorithms:

Rand Score: A metric measuring the similarity between true and predicted clusters, the Rand Score quantifies the accuracy of cluster assignments in a range from 0 to 1.

Calinski-Harabasz Index: A metric evaluated by the ratio of between-cluster variance to within-cluster variance, the Calinski-Harabasz Index assesses clustering quality based on compact, well-separated clusters.

Silhouette Score: A metric gauging how well-defined and separated clusters are, the Silhouette Score ranges from -1 to 1, with higher values indicating better-defined clusters.

Davies-Bouldin Index: A metric quantifying the compactness and separation of clusters by evaluating the similarity between each cluster and its most similar neighbor, with lower values indicating better-defined clusters.


The descriptions for the algorithms and their scores are below:


## HDBSCAN
Hierarchical Density-Based Spatial Clustering of Applications with Noise

HDBSCAN identifies clusters of varying shapes and densities, offering robust performance in noisy datasets by focusing on local density variations.

![Screenshot 2023-11-25 234909](https://github.com/kennethjy/DataScienceF9/assets/114073455/bcb2d76e-9a6b-4cc2-8c6f-74a0a3d06f02)

## BIRCH
Balanced Iterative Reducing and Clustering using Hierarchies

A hierarchical clustering algorithm ideal for large datasets, BIRCH efficiently forms clusters by incrementally summarizing data.

![Screenshot 2023-11-25 234844](https://github.com/kennethjy/DataScienceF9/assets/114073455/d7b10d3e-baf3-4157-adc1-927149cd40e0)

## Spectral Clustering
A partitioning algorithm using eigenvalues of the similarity matrix to reveal the underlying structure of data, effectively grouping similar instances even when clusters have complex shapes or sizes.

![Screenshot 2023-11-25 234829](https://github.com/kennethjy/DataScienceF9/assets/114073455/c720b282-eaab-417b-9176-76d7f07f3901)

## Kmeans
A partitioning algorithm that partitions data into K clusters by iteratively minimizing the within-cluster variance, producing spherical clusters based on feature similarity

![Screenshot 2023-11-25 235041](https://github.com/kennethjy/DataScienceF9/assets/114073455/fd63e974-b697-43dd-9156-ff7e6127ef46)

## Best Algorithms:

Rand Score - Kmeans

Calinski & Harabasz Score - Kmeans

Silhouette Score - Spectral Clustering

Davies-Bouldin Index - Spectral Clustering
