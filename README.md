# SmartCart Customer Segmentation System

## Overview

This project builds a customer segmentation model using Machine Learning to group customers based on behaviour, income, and spending patterns.

The system works as a data-driven solution that can help organizations understand different customer types and improve decision making.

---

## What This Project Does

- Analyzes customer demographic and purchasing data
- Identifies hidden behaviour patterns
- Groups similar customers together
- Generates meaningful customer segments

This type of system can be used by:

- E-commerce platforms
- Retail businesses
- Marketing teams
- CRM analytics teams

---

## Machine Learning Model

This is an Unsupervised Machine Learning project.

### Algorithms Used

- K-Means Clustering
- Agglomerative (Hierarchical) Clustering
- PCA (Dimensionality Reduction)

---

## Model Training Steps

1. Data Cleaning
2. Missing Value Handling
3. Feature Engineering
4. Encoding Categorical Data
5. Feature Scaling
6. PCA Transformation
7. Model Training
8. Cluster Visualization

---

## Model Evaluation

Since this is a clustering problem, accuracy is not applicable.

Cluster quality was evaluated using:

- Elbow Method (WCSS)
- Silhouette Score

---

## Final Result

- Optimal number of clusters: **4**
- Customers segmented into distinct behaviour groups
- Clear cluster separation after PCA visualization

---

## Features Engineered

- Age
- Customer Tenure
- Total Spending
- Family Size Indicators

---

## Practical Use Cases

- Identify high-value customers
- Detect low engagement users
- Targeted marketing campaigns
- Improve customer retention
- Business decision support

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## How to Run

```bash
git clone https://github.com/sagarjain2205/smartcart-clustering-system.git
