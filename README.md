# 🛍️ Customer Segmentation using Clustering

This project performs customer segmentation using K-Means and Agglomerative Clustering on a dataset containing customer demographics and behavioral metrics. The goal is to group similar customers based on features like Age, Annual Income, and Spending Score to support targeted marketing strategies.

---

## 📂 Dataset Overview

The dataset contains the following features:

| Column Name           | Description                          |
|-----------------------|--------------------------------------|
| `CustomerID`          | Unique identifier for each customer  |
| `Gender`              | Customer gender                      |
| `Age`                 | Customer age                         |
| `Annual Income (k$)`  | Annual income in thousands of USD    |
| `Spending Score (1-100)` | Customer spending behavior score |

---

## 🧪 Project Workflow

### 🔍 1. Exploratory Data Analysis (EDA)
- Checked for missing values and data types
- Analyzed distribution of age, income, and spending score
- Visualized relationships between variables using:
  - Histograms
  - Scatter Plot
  - Heatmaps
- Gender-wise income and spending behavior analysis

### 🤖 2. Feature Selection
- Selected relevant features: `Age`, `Annual Income (k$)`, and `Spending Score`
- Normalized/standardized features for clustering

### 📊 3. Clustering Approaches

#### 📌 K-Means Clustering
- Used **Elbow Method** to determine optimal number of clusters
- Fitted `KMeans` and labeled customer segments
- Visualized clusters using 2D and 3D plots

#### 📌 Agglomerative Clustering
- Applied hierarchical clustering with dendrogram
- Compared results with K-Means clusters
- Visualized segment formation

---

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🎯 Key Insights
- Identified distinct customer groups (e.g., high-income low-spenders, young high-spenders)
- Hierarchical clustering revealed finer sub-group behavior
- Useful for targeted marketing and personalized campaigns



