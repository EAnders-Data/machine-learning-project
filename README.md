# machine-learning-project
# Customer Segmentation using K-Means Clustering

This project performs customer segmentation on mall customer data using the K-Means clustering algorithm. It scales numerical features, identifies the optimal number of clusters using the Elbow Method, and trains a K-Means model.

## Features & Workflow

1. **Data Preprocessing:** Standardizes features (`Income` and `SpendingScore`) using `StandardScaler`.
2. **Optimal Cluster Selection:** Utilizes the **Elbow Method** (plotting WCSS / Inertia across $k \in [1, 10]$) to find the optimal number of clusters.
3. **Model Training:** Fits a `KMeans` model with $k = 5$ clusters (`k-means++` initialization).

## Requirements

Ensure you have Python 3 installed along with the following packages:

```bash
pip install pandas numpy matplotlib scikit-learn
