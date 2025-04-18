# Clustering
# 🌸 Iris Dataset Clustering Project

This project explores various **clustering techniques** on the classic [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) from the UCI Machine Learning Repository. It includes different **preprocessing approaches**, applies clustering algorithms, evaluates them using standard metrics, and visualizes the results.

---

## 📂 Dataset Used

- **Name**: Iris Dataset  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
- **Instances (Rows)**: 150  
- **Features (Columns)**: 4 numerical features
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

---

## 🔄 Preprocessing Approaches

We applied the following transformations to the dataset before clustering:

1. **No Data Processing** – raw data
2. **Normalization** – Min-Max scaling to [0, 1]
3. **T+N** – Standard Scaling followed by Normalization
4. **T+N+PCA** – Standard Scaling → Normalization → PCA (2 components)

---

## 🔍 Clustering Techniques

We applied the following unsupervised clustering algorithms:

- **K-Means**
- **Hierarchical (Agglomerative Clustering)**
- **K-Means Shift** 

---

## 📈 Evaluation Metrics

Each clustering combination was evaluated using:

- **Silhouette Score**
- **Calinski-Harabasz Score**
- **Davies-Bouldin Score**

The optimal clustering combination was identified based on **Silhouette Score**.

---

## 📊 Results Summary

- ✅ **Best Algorithm**: `K-Means Shift`
- ✅ **Best Number of Clusters**: `2`
- ✅ **Best Preprocessing**: `No Data Processing`
- ✅ **Best Silhouette Score**: 0.68

---

## 📁 Output Files

- `iris_clustering_results.csv`: Raw metric scores  
- `formatted_clustering_tables.xlsx`: Excel file with formatted comparison tables  
- `cluster_plots.png`: Visualizations of clustering results  
- `silhouette_heatmap.png`: Heatmap of silhouette scores across all combinations

---

## 📦 Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn '''

---

## Contributors
[Kartik Sidana]

