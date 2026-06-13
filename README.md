# Customer Segmentation Using K-Means Clustering

## Synent Technologies Data Science Internship

### Task 6 – Customer Segmentation

---

# Problem Statement

Businesses often serve customers with different spending habits and income levels.

Understanding customer behavior helps organizations:

- Improve marketing effectiveness
- Increase customer retention
- Personalize offers
- Improve business profitability

The goal of this project is to segment customers into distinct groups based on Annual Income and Spending Score using the K-Means Clustering algorithm.

---

# Dataset Details

Dataset Name:
Mall Customer Segmentation Dataset

Source:
Kaggle

Dataset Link:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Records:
200 Customers

Features:

| Feature | Description |
|----------|------------|
| CustomerID | Unique Customer Identifier |
| Gender | Male/Female |
| Age | Customer Age |
| Annual Income (k$) | Annual Income |
| Spending Score (1-100) | Spending Behavior Score |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# Project Workflow

## 1. Data Collection

Loaded Mall Customer Dataset.

## 2. Data Understanding

- Shape Analysis
- Data Types
- Statistical Summary

## 3. Data Cleaning

- Missing Value Check
- Duplicate Check

Result:
No missing values found.
No duplicate records found.

## 4. Exploratory Data Analysis

Performed:

- Gender Distribution Analysis
- Age Distribution Analysis
- Income Distribution Analysis
- Spending Score Distribution Analysis

---

# Visualizations

## Gender Distribution

Shows distribution of male and female customers.

## Age Distribution

Shows age concentration of customers.

## Income Distribution

Shows annual income variation among customers.

## Spending Score Distribution

Shows customer spending patterns.

## Elbow Method

Used to determine optimal number of clusters.

## Customer Segments

Visual representation of customer groups.

---

# Feature Selection

Selected Features:

- Annual Income (k$)
- Spending Score (1-100)

Reason:

These features best represent customer purchasing behavior.

---

# Feature Scaling

StandardScaler was applied to normalize the data before clustering.

---

# K-Means Clustering

Algorithm:
K-Means Clustering

Optimal Number of Clusters:
K = 5

The Elbow Method indicated that 5 clusters provide the best segmentation.

---

# Cluster Insights

## Cluster 0

- Medium Income
- Medium Spending

Business Category:
Regular Customers

---

## Cluster 1

- High Income
- High Spending

Business Category:
Premium Customers

---

## Cluster 2

- Low Income
- High Spending

Business Category:
Promotion Responsive Customers

---

## Cluster 3

- High Income
- Low Spending

Business Category:
Potential Customers

---

## Cluster 4

- Low Income
- Low Spending

Business Category:
Low Priority Customers

---

# Results

Successfully segmented customers into five distinct groups.

Achievements:

- Data Cleaning Completed
- EDA Performed
- Feature Scaling Applied
- Elbow Method Implemented
- K-Means Clustering Applied
- Customer Segments Visualized
- Business Insights Generated

---

# Business Value

Customer segmentation can help businesses:

- Improve customer targeting
- Increase sales
- Enhance marketing efficiency
- Improve customer satisfaction

---

# Conclusion

This project demonstrates how unsupervised machine learning can identify meaningful customer groups.

The K-Means algorithm successfully segmented customers into five clusters based on income and spending behavior.

These insights can support better business decision-making and personalized marketing strategies.

---


# Author

Shivansh Dalvadi

Synent Technologies Internship Project
