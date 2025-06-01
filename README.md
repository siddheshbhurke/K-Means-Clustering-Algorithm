# K-Means-Clustering-Algorithm
This project performs unsupervised clustering on the Iris dataset using the K-Means algorithm. It includes data preprocessing, cluster optimization using the Elbow Method, dimensionality reduction with PCA for visualization, and analysis of cluster-wise feature distributions.
---
## 📁 Dataset
- File: 1) iris.csv
- Attributes: Sepal Length, Sepal Width, Petal Length, Petal Width, Species (optional)
- Note: The script dynamically handles the presence or absence of the species column.
---
## 🛠️ Requirements
Install the following Python packages before execution:
```
pip install pandas matplotlib seaborn scikit-learn
```
---
## 📊 Key Operations : 
### 1. Preprocessing 
- Standardizes features using StandardScaler.
- Removes species column if present to ensure unsupervised clustering.
  
### 2. Optimal Cluster Detection
- Uses Elbow Method to identify the best value of k by plotting Within-Cluster Sum of Squares (WCSS).

### 3. K-Means Clustering
- Performs clustering with k = 3 (configurable).
- Assigns cluster labels to the original DataFrame.

### 4. Dimensionality Reduction
- Applies Principal Component Analysis (PCA) to reduce feature space to 2D.
-Visualizes clusters using Seaborn's scatterplot.

### 5. Cluster Analysis
- Outputs mean values of features per cluster to interpret the clustering output.
---

## 📈 Visual Outputs

### Elbow Curve: 
To determine the optimal number of clusters.

### Cluster Plot (PCA-reduced): 
For intuitive 2D visualization of high-dimensional clusters.
---

## 📌 How to Run
```python kmeans_iris.py```
- Ensure 1) iris.csv is present in the working directory.
---

## 📄 Output 
- Elbow Method plot
- PCA-reduced cluster scatterplot
-Printed summary of cluster-wise mean feature values
---

## ✅ Example Use Case
This script is ideal for:
- Learning unsupervised learning workflows
- Visualizing clusters in high-dimensional data
- Gaining insight into feature-based separation of classes (e.g., species in Iris dataset)
---
## 🔒 License
This project is open-source and free to use for academic and research purposes.
---




