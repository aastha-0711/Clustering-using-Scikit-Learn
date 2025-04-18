# 📊 Clustering using Scikit-Learn

This project presents a comparative study of three clustering algorithms—**KMeans**, **Hierarchical Clustering**, and **Mean Shift**—applied to the Iris dataset under various data preprocessing strategies.

---

## 🔍 Objective

To identify the most effective clustering algorithm and preprocessing combination for the Iris dataset using standard evaluation metrics.

---

## 🧠 Algorithms Compared

- **KMeans Clustering**  
- **Agglomerative (Hierarchical) Clustering**  
- **Mean Shift Clustering**

---

## ⚙️ Preprocessing Techniques Applied

Six different preprocessing pipelines were tested:

- **Raw Data** *(No preprocessing)*  
- **Normalization** *(MinMaxScaler)*  
- **Standardization** *(StandardScaler)*  
- **PCA** *(Principal Component Analysis with 2 components)*  
- **Standardization + Normalization** *(T+N)*  
- **Standardization + Normalization + PCA** *(T+N+PCA)*

---

## 📈 Evaluation Metrics

Clustering performance was assessed using:

- **Silhouette Score**  
- **Calinski-Harabasz Index**  
- **Davies-Bouldin Score**

These metrics provide insights into cluster cohesion, separation, and density.

---

## 📊 Visualizations

- Bar plots were created to compare **Silhouette Scores** across algorithms and preprocessing strategies.
- Each chart provides a clear view of how preprocessing affects clustering quality.

---

## 🏆 Best Performing Configuration

From the comparative analysis:

- **Best Algorithm:** KMeans Clustering  
- **Best Score (Silhouette):** **5.67**  
- **Best Preprocessing:** Standardization + Normalization + PCA *(T+N+PCA)*  

KMeans consistently outperformed the other methods in this setup, demonstrating optimal cluster formation and separation.

---

## 🗃️ Dataset

- **Name:** Iris Dataset  
- **Source:** `sklearn.datasets.load_iris()`  
- **Features:** 4 (Sepal Length, Sepal Width, Petal Length, Petal Width)  
- **Classes:** 3

---

## 📝 Requirements

Make sure to have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
