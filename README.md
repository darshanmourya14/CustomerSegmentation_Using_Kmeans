📊 Customer Segmentation & BI Dashboard

🔎 Project Overview

This project applies unsupervised machine learning to segment customers based on income and spending behavior. The clustering results are integrated into a Power BI dashboard to enable KPI-based analysis and interactive business reporting.

The objective is to transform raw customer data into actionable segments that support marketing strategy and decision-making.

🎯 Business Objective

Businesses often struggle to identify high-value and low-engagement customers.
This project aims to:

Group customers using behavioral patterns

Quantify segment distribution and spending trends

Translate machine learning output into business insights

Enable dashboard-driven analysis for stakeholders

🛠 Tools & Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Techniques

Exploratory Data Analysis (EDA)

Feature Scaling (StandardScaler)

K-Means Clustering

Silhouette Score Validation

SQL-style Aggregation

Business Intelligence

Power BI

DAX Measures

Interactive Dashboard Design

⚙️ Project Workflow

Data Loading & Cleaning

Exploratory Data Analysis

Feature Selection (Income & Spending Score)

Data Scaling using StandardScaler

K-Means Clustering

Cluster Validation using Silhouette Score

KPI-based Cluster Profiling

Export of Segmented Dataset

Power BI Dashboard Development

📈 Dashboard Highlights

The Power BI dashboard includes:

Total Customer KPI

Average Spending Score KPI

Customer Distribution by Segment

Income vs Spending Scatter Visualization

Interactive filtering by customer segment

💡 Key Insights

Distinct customer groups emerge based on spending behavior.

High-income high-spending clusters represent premium customers.

Moderate-income segments show varied engagement levels.

Segmentation enables targeted marketing and retention strategies.

📂 Repository Structure
customer-segmentation-powerbi/
│
├── customer_segmentation.ipynb
├── segmented_customers_output.csv
├── Customer_Segmentation_Dashboard.pbix
└── README.md
🚀 Business Value

This project demonstrates how machine learning can be operationalized into a reporting environment.
It bridges data science and business intelligence by converting clustering outputs into dashboard-ready KPIs.
