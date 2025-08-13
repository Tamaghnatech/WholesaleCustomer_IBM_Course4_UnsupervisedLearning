<img src="IBM%20Logo.png" alt="IBM Logo" width="40"/> #IBM ML Course 4 — Wholesale Customer Segmentation (Unsupervised ML)

![Certificate](certificate.png)
![Badge](unsupervised-machine-learning.png)

Wholesale customer segmentation using unsupervised machine learning techniques such as clustering and dimensionality reduction (PCA, t-SNE, UMAP).  
Built in Google Colab using Python (Pandas, Scikit-learn, Matplotlib, Seaborn) as part of the IBM Data Science curriculum on Coursera.

---

## 📜 Project Overview
This project is part of **IBM Machine Learning Professional Certificate — Course 4: Unsupervised Machine Learning**.  
The goal is to perform **customer segmentation** for a wholesale distributor using **unsupervised learning techniques** such as **K-Means**, **Agglomerative Clustering**, and **DBSCAN**, and dimensionality reduction methods like **PCA**, **t-SNE**, and **UMAP**.

The final output includes **visual comparisons** of clustering methods, PCA loadings, and projections, enabling a data-driven segmentation strategy.

---

## 📂 Dataset
**Source:** [Wholesale Customers Dataset](https://archive.ics.uci.edu/ml/datasets/wholesale+customers)  
- **Rows:** 440  
- **Columns:** 8 (Annual spending on different product categories + Region & Channel)
- **Target Variable:** None (unsupervised)
- **Preprocessing:** StandardScaler applied, outlier removal using IQR, dimensionality reduction.

---

## 🛠 Techniques & Methods Used
- **Exploratory Data Analysis (EDA)**
  - Correlation heatmaps
  - Distribution plots
  - Pairwise scatter plots

- **Dimensionality Reduction**
  - **PCA** (Scree plots, loadings, biplots)
  - **t-SNE**
  - **UMAP**

- **Clustering Algorithms**
  - K-Means (Elbow Method, Silhouette Score)
  - Agglomerative Clustering
  - DBSCAN

- **Evaluation**
  - Silhouette Coefficient
  - Davies–Bouldin Index
  - Visual cluster separation

---

## 📊 Key Visuals
| Visualization | Description |
|---------------|-------------|
| **Correlation Heatmap** | Shows relationships between product categories. |
| **PCA Scree Plot & Cumulative Variance** | Helps decide number of components. |
| **PCA Loadings** | Feature contribution to each principal component. |
| **PCA, t-SNE, UMAP Projections** | Visual separation of customer segments. |
| **Algorithm Comparison Plot** | Silhouette/Davies-Bouldin scores for all algorithms. |

---

## 🚀 Results
- **Optimal K** for K-Means = **3**
- PCA captured **85% variance** in 3 components.
- DBSCAN revealed some noise/outlier customers not grouped in other methods.
- t-SNE & UMAP gave better **cluster separation** in low-dimensional space.

---

## 📌 Learning Outcomes
- Applied **unsupervised ML** to a real-world dataset.
- Compared **clustering algorithms** effectively.
- Understood **dimensionality reduction’s role** in cluster visualization.
- Produced **publication-ready** visualizations.

---

## 🏆 Credential
**IBM Machine Learning Professional Certificate – Course 4**  
[Verify Credential](https://www.credly.com/badges/XXXXX)

---

## 📬 Contact
**Tamaghna Nag**  
📍 London, UK | Kolkata, India  
📧 tamaghnanag04@gmail.com  
🌐 [Portfolio](https://tamaghnatech.in) | [GitHub](https://github.com/Tamaghnatech) | [LinkedIn](https://www.linkedin.com/in/tamaghna99/)

---
