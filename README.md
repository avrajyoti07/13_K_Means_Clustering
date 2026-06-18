# 📊 Customer Segmentation — K-Means Clustering

An unsupervised machine learning project that segments people into **3 income groups** based on **Age** and **Income** using **K-Means Clustering**, with feature scaling and the Elbow Method for optimal K selection.

## 📌 What It Does
- Loads an income dataset with `Name`, `Age`, and `Income` columns
- Visualizes raw data distribution using a scatter plot
- Scales features using **MinMaxScaler** for better clustering
- Applies **K-Means Clustering** with `n_clusters=3`
- Assigns each person to a cluster (0, 1, or 2)
- Visualizes the 3 clusters with distinct colors (green, blue, red)
- Uses the **Elbow Method** (SSE plot) to determine the optimal number of clusters

## 🔢 Clusters Identified
| Cluster | Group |
|---------|-------|
| 0 | Low income / Young |
| 1 | Mid income / Middle-aged |
| 2 | High income / Older |

## 📈 Elbow Method
The SSE (Sum of Squared Errors) plot shows a sharp elbow at **K=3**, confirming 3 is the optimal number of clusters.

## 🚀 Run It

**1. Install dependencies:**
```bash
pip install jupyter pandas scikit-learn matplotlib
```

**2. Launch the notebook:**
```bash
jupyter notebook 12k_Means_Clustering.ipynb
```

## 🛠️ Built With
Python · Pandas · Scikit-learn · Matplotlib · Jupyter Notebook
