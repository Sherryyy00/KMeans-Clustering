# KMeans Clustering on Iris Dataset with Interactive Visualizations

## Description

This project applies the KMeans clustering algorithm to the well-known Iris dataset. The goal is to perform clustering on the dataset and visualize the results interactively using Plotly. The project includes two main parts:

1. **Elbow Method**: Determines the optimal number of clusters.
2. **Cluster Visualization**: Visualizes the clusters and centroids interactively.

## Prerequisites

- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `plotly`

You can install the required libraries using pip:

    pip install pandas numpy scikit-learn matplotlib plotly

## Usage

### Elbow Method

The script first calculates the Within-Cluster Sum of Squares (WCSS) for different numbers of clusters (from 1 to 10). It then generates an interactive plot to visualize the elbow point, helping to determine the optimal number of clusters.

### KMeans Clustering

- The script applies KMeans with 3 clusters to the Iris dataset.
- It generates an interactive scatter plot of the first two features (sepal length and sepal width) of the Iris dataset, color-coded by the predicted cluster.
- The centroids of the clusters are also plotted.

## Analysis of Results

### Elbow Method

The Elbow Method was used to determine the optimal number of clusters for the Iris dataset. The WCSS was calculated for 1 to 10 clusters, and the results were plotted. The "elbow" in the graph indicates the point where adding more clusters doesn't significantly reduce the WCSS, suggesting the optimal number of clusters.
<p align="center">
  <img src="https://github.com/Sherryyy00/KMeans-Clustering/blob/main/Graphs/graph1.png " width="50%" height="50%">
</p>
**Observation**:

- The elbow is observed at **3 clusters**, which aligns with the known classification of the Iris dataset into three species: _Iris-setosa_, _Iris-versicolour_, and _Iris-virginica_.

### KMeans Clustering

KMeans clustering was performed with 3 clusters. The results were visualized by plotting the first two features (sepal length and sepal width) of the Iris dataset. The clusters are well-separated, and the centroids are displayed on the plot.
<p align="center">
  <img src="https://github.com/Sherryyy00/KMeans-Clustering/blob/main/Graphs/graph2.png " width="50%" height="50%">
</p>
**Observation**:

- The clusters correspond closely to the three species of Iris flowers.
- The centroids (marked in yellow) represent the mean position of the data points in each cluster.
- _Iris-setosa_ is the most distinct cluster, while _Iris-versicolour_ and _Iris-virginica_ are closer to each other, indicating some overlap in features.

### Conclusion

- The clustering results are consistent with the actual species classification of the Iris dataset.
- KMeans successfully identified the natural grouping of the data, validating the effectiveness of this algorithm for this type of analysis.



   


