# KMeans-Clustering-on-Iris-Dataset

# K-Means Clustering with Iris Dataset

This project demonstrates the use of K-Means clustering on the Iris dataset. K-Means is an unsupervised machine learning algorithm that groups data points into clusters based on similarity.

## Overview

The script performs the following tasks:

1. **Loading the Dataset**: The Iris dataset is used, which contains data about the sepal and petal dimensions of three different species of Iris flowers. This dataset has 150 samples, each with four features: sepal length, sepal width, petal length, and petal width.

2. **Data Preprocessing**:
   - **Standardization**: The dataset is standardized, meaning each feature is scaled to have a mean of 0 and a variance of 1. This step is crucial because K-Means is sensitive to the scale of the data.

3. **K-Means Clustering**:
   - The **K-Means** algorithm is applied with **K=3** clusters, since there are three species of Iris flowers in the dataset.
   - The K-Means algorithm assigns each data point to one of the clusters based on the similarity of the features.

4. **Visualization**:
   - A scatter plot is created using the first two features (sepal length and sepal width) to visually inspect how the data points are clustered.
   - Each point is colored based on the cluster it belongs to, making it easy to see how the algorithm has grouped the data.

## Key Concepts

- **K-Means Clustering**: K-Means is a partitioning method where the data is divided into K distinct groups (clusters). The algorithm iteratively assigns data points to the nearest cluster centroid and recalculates the centroid positions until convergence.

- **Standardization**: Standardizing the data helps ensure that all features contribute equally to the distance calculation in the K-Means algorithm. Without standardization, features with larger numerical ranges could dominate the clustering process.

- **Cluster Centroids**: K-Means finds the "center" of each cluster, which is the mean of the data points assigned to that cluster. These centroids are used to assign new data points to the nearest cluster.

## Requirements

To run the project, make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using the following:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
