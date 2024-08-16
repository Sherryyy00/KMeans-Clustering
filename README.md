# Iris Clustering with K-Means

This project applies the K-Means clustering algorithm to the Iris dataset. The Iris dataset is a famous dataset in machine learning and statistics, which contains 150 observations of iris flowers, with four features for each observation: sepal length, sepal width, petal length, and petal width. The goal is to cluster the dataset into three clusters, corresponding to the three species of iris flowers.

## Project Overview

The project demonstrates the following key steps:

1. **Loading the Iris Dataset**:
   - The Iris dataset is loaded using the `sklearn.datasets` module.
   - The data is converted into a Pandas DataFrame for easy manipulation and visualization.

2. **The Elbow Method**:
   - The Elbow Method is used to determine the optimal number of clusters for K-Means clustering.
   - The Within-Cluster Sum of Squares (WCSS) is calculated for a range of cluster numbers (1 to 10).
   - A plot is generated to visualize the WCSS against the number of clusters.

3. **K-Means Clustering**:
   - The K-Means algorithm is applied to the dataset, with the number of clusters set to 3.
   - The dataset is then classified into the identified clusters.

4. **Visualizing the Clusters**:
   - The clusters are visualized using a scatter plot of the first two features (sepal length and sepal width).
   - The centroids of the clusters are also plotted.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- scikit-learn

You can install the required libraries using the following command:

    pip install pandas numpy matplotlib scikit-learn


## How to Run

1. Clone the repository:

    ```bash
   git clone https://github.com/yourusername/iris-kmeans-clustering.git
    ```

2. Navigate to the project directory:

    ```bash
    cd iris-kmeans-clustering
    ```

3. Run the script:

    ```bash
    python iris_kmeans.py
    ```

This will execute the script and display the plots generated during the clustering process.

## Project Structure

- `iris_kmeans.py`: The main Python script that runs the clustering algorithm and generates the plots.
- `README.md`: Documentation file (



