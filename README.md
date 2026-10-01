# Wheat Grain Clustering using DBSCAN

This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to the Seeds dataset to discover natural groups of wheat grains based on their physical characteristics.

The main goal of this project is to perform **unsupervised clustering** without using predefined class labels and to identify unusual observations that do not belong to any dense cluster.

---

## 📌 Project Objective

The objective of this project is to:

- Apply DBSCAN clustering to wheat grain data
- Standardize the features before clustering
- Determine a suitable `eps` value using a distance plot
- Discover natural groups within the dataset
- Identify noise/outlier observations
- Visualize the resulting clusters
- Analyze the characteristics of each cluster

##  Algorithm Used

### DBSCAN

DBSCAN is a density-based unsupervised machine learning algorithm.

Unlike algorithms such as K-Means, DBSCAN does not require the number of clusters to be specified beforehand.

It groups observations based on the density of neighboring points and can also identify observations that do not belong to any dense cluster.

   ↓
Cluster-wise Analysis
