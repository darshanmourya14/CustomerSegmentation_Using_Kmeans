# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs customer segmentation using unsupervised machine learning. The goal is to group customers based on purchasing behavior and income patterns to help businesses identify high-value segments and improve marketing strategies.

The analysis follows a structured data analytics workflow including preprocessing, clustering, validation, and business interpretation.

---

## 🎯 Problem Statement

Businesses often struggle to understand different types of customers.
This project uses K-Means clustering to identify distinct customer groups based on:

* Annual Income
* Spending Score

The output helps identify premium customers, average buyers, and low-engagement segments.

---

## 🗂 Dataset

Mall Customer Segmentation Dataset

Features used:

* Annual Income (k$)
* Spending Score (1–100)

---

## ⚙️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* PCA (Principal Component Analysis)

---

## 🔎 Project Workflow

1. Data Loading and Understanding
2. Data Cleaning and Feature Selection
3. Feature Scaling using StandardScaler
4. Optimal Cluster Selection using Elbow Method
5. K-Means Model Training
6. Cluster Validation using Silhouette Score
7. Visualization of Clusters
8. PCA-based Dimensionality Reduction
9. Business Interpretation of Customer Segments

---

## 📊 Key Techniques Used

* K-Means Clustering
* StandardScaler
* Elbow Method
* Silhouette Score
* PCA Visualization

---

## 📈 Key Insights

* High income + high spending customers form premium segments.
* Low income + low spending customers represent price-sensitive groups.
* Mid-income clusters show varied spending behavior, indicating potential marketing opportunities.

---

## 📷 Visualizations

* Elbow Method Plot
* Cluster Scatter Plot
* PCA Cluster Projection

---

## 📁 Repository Structure

Customer-Segmentation-KMeans/

data/
Mall_Customers.csv

notebook/
customer_segmentation.ipynb

README.md

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries:
   pip install pandas numpy matplotlib scikit-learn
3. Open the notebook and run all cells

---

## 💡 Business Value

Customer segmentation helps companies:

* Target marketing campaigns
* Improve customer retention
* Identify high-value customers
* Optimize pricing strategies

---

## 👤 Author

Data Analytics Project – Customer Segmentation using K-Means
