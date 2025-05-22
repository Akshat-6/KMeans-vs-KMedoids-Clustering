# KMeans-vs-KMedoids-Clustering
🌸 Iris Dataset – K-Means vs K-Medoids Clustering

This project presents a comparative analysis of K-Means and K-Medoids clustering algorithms on the classic Iris dataset. The objective is to evaluate the performance of both clustering techniques and visualize the differences in clustering behavior.

📌 Objective
Apply K-Means and K-Medoids clustering on the Iris dataset.

Compare performance based on metrics like inertia, silhouette score, and clustering accuracy.

Visualize clusters formed by both algorithms.

📊 Dataset
Dataset used: Iris Dataset

Available from: sklearn.datasets.load_iris() or UCI Machine Learning Repository

🛠️ Tasks Performed
✅ 1. Data Loading & Exploration
Loaded dataset using Scikit-learn.

Performed basic EDA to understand feature distribution and class balance.

✅ 2. Data Preprocessing
Normalized features for better clustering performance.

Removed target labels for unsupervised learning.

✅ 3. K-Means Clustering
Applied KMeans from sklearn.cluster.

Evaluated performance using:

Inertia

Silhouette Score

Adjusted Rand Index (if comparing with actual labels)

✅ 4. K-Medoids Clustering
Applied KMedoids from sklearn_extra.cluster or pyclustering.

Similar evaluation metrics were used for comparison.

✅ 5. Visualization
Plotted clusters using:

2D Scatter plots (with PCA for dimensionality reduction)

Cluster centroids and boundaries

✅ 6. Results & Analysis
Compared both algorithms based on performance metrics and visual patterns.

💻 Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

scikit-learn-extra (for K-Medoids)

🚀 Conclusion
K-Means is faster but may be sensitive to outliers.

K-Medoids is more robust but computationally heavier.

Each algorithm has its use case depending on data characteristics.




