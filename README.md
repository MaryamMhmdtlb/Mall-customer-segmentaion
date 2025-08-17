# Mall Customer Segmentation

This project applies clustering techniques to segment mall customers based on demographic and behavioral data. The goal is to identify distinct customer groups that can help businesses improve marketing strategies, targeted promotions, and customer relationship management

## 📌 Overview

Customer segmentation is one of the most important applications of unsupervised learning in marketing.
In this project, we explore the Mall Customer Dataset and apply clustering algorithms such as K-Means and K-Prototypes to group customers by their Annual Income, Spending Score, Age, and Gender.

## 📊 Dataset

The dataset contains customer information including:

  * CustomerID

  * Gender

  * Age

  * Annual Income (k$)

  * Spending Score (1–100)

👉 Dataset Source: Mall Customer Dataset on Kaggle

## ⚙️ Methods

Data Preprocessing:

  * Handling categorical features (e.g., Gender).
  
  * Standardization of numerical features.
  
  * Clustering Algorithms Used:
  
  * K-Means (for numerical features).
  
  * K-Prototypes (for mixed categorical and numerical data).
  
  * Evaluation:
  
  * Elbow Method
  
  * Silhouette Score

## 📈 Results

Optimal number of clusters determined using the Elbow Method and Silhouette Score.

Final segmentation grouped customers into meaningful clusters such as:

  - High Income – High Spending (Premium customers).
  
  - Low Income – High Spending (Price-sensitive but active buyers).
  
  - High Income – Low Spending (High potential, low engagement).
  
  - Average Income – Moderate Spending (Typical mall visitors).
  
  - Low Income – Low Spending (Least profitable segment).

Sample Visualizations

Elbow Method Curve showing the optimal k.

Scatter Plot of clusters based on Annual Income and Spending Score.

Centroids Marked on scatter plots for clarity
