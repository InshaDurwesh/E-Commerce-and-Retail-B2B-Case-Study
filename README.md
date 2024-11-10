# E-Commerce-and-Retail-B2B-Case-Study

## Project Overview

This project aims to analyze and provide insights into the factors contributing to delayed payments in a B2B e-commerce and retail environment. Using various data analysis techniques, including outlier removal, data scaling, and clustering, we identified key drivers of payment delays and developed actionable insights to improve payment processes. The project utilizes a real-world dataset to demonstrate the application of machine learning and data preprocessing techniques in the B2B space.

## Project Objectives

- **Identify Key Contributors to Delayed Payments**: Analyze factors such as payment terms, invoice amounts, and currency codes.
- **Data Preprocessing**: Remove outliers and standardize data to ensure accurate clustering.
- **Clustering Analysis**: Apply K-Means clustering to group similar data and determine the optimal number of clusters.
- **Insight Generation**: Provide actionable recommendations based on the clustering results and payment delay factors.

## Key Insights

- **USD Amount** is the primary contributor to delayed payments, followed by **credit period** and **payment terms** like "30 Days from EOM" and "60 Days from EOM."
- The data showed a moderate imbalance, with approximately 66% of entries being delayed.
- By identifying these key contributors, we aim to improve payment timelines and optimize payment processing strategies.

## Methodology

1. **Outlier Removal**: Used the Interquartile Range (IQR) method to remove outliers and ensure accurate analysis.
2. **Data Scaling**: Applied Standard Scaler to standardize the dataset and ensure equal feature contribution in clustering.
3. **Clustering**: Applied K-Means clustering and used the Elbow Curve and Silhouette Score methods to select the optimal number of clusters.
4. **Data Imbalance Considerations**: Noted that a moderate imbalance in the dataset (66% delayed payments) may affect clustering results.

## Tools & Technologies

- **Python**: For data analysis and clustering
- **Pandas**: For data manipulation
- **Scikit-learn**: For clustering and scaling
- **Matplotlib/Seaborn**: For visualizations
- **Jupyter Notebook**: For running the analysis and documentation

