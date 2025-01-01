# IS405.P11.HTCL - Big Data

## Course Information
- **Course**: IS405.P11.HTCL - Big Data
- **Lecturer**: MSc. Nguyễn Hồ Duy Tri
- **Semester**: 1, 2024-2025  

## Team Information
## Team Information
| No. | Student ID | Full Name           |
| --- | ---------- | ------------------- |
| 1   | 21520596   | Tran Thi Kim Anh (Leader)   |
| 2   | 21521049   | Ho Quang Lam        |
| 3   | 21521586   | Le Thi Le Truc  |
| 4   | 21521882   | Le Minh Chanh       |


## Project Information
- **Project Title**: `APPLICATION OF CLUSTERING ALGORITHMS FOR CUSTOMER DATA ANALYSIS IN A BIG DATA ENVIRONMENT`
- **Dataset**: [Predicting Credit Card Customer Segmentation](https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m)

## Overview dataset
- 10.127 rows and 23 columns
- Containing customer information collected from the consumer credit card portfolio, including demographic data, relationships with card providers, spending behaviors, and predictive indicators from the consumer credit card portfolio.

## Summary
- **Objective**: The project aims to apply clustering algorithms to analyze customer data in a big data environment.
- **Method**: 
  - Data preprocessing: Handle missing values, use **StringIndexer** to encode categorical features, use **Z-Score** to normalize numerical features, and use **PCA** to reduce dimensionality.
  - Clustering: Apply **K-Means**, **DHC (Divisive Hierachical Clustering)** algorithms to segment customers.
  - Evaluation: Evaluate the performance of clustering algorithms using the **silhouette score** and **calinski harabasz score**.
  - Visualization: Visualize the results of clustering algorithms.
- **Result**: Extract specific customers from each group to propose appropriate marketing strategies.

## Technology:
- **Environment**: Spark 
- **Language**: Python
- **Tools**: PySpark, Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn





