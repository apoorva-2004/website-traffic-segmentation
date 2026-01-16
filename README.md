# Website Traffic Segmentation via Clustering

## Project Overview
This project segments website visitors based on their behavior using unsupervised learning (K-Means clustering).
The goal is to identify different types of users based on engagement metrics.

## Dataset
The dataset contains website traffic metrics such as:
- Page Views
- Average Session Duration
- Bounce Rate
- New and Returning Users
- Conversions

Note: The dataset was provided as a MySQL dump (CSV format) and loaded directly into Python.

## Tools Used
- Python
- pandas
- scikit-learn
- seaborn
- matplotlib

## Methodology
1. Performed Exploratory Data Analysis (EDA)
2. Selected relevant numeric engagement features
3. Normalized data using StandardScaler
4. Applied K-Means clustering (3 clusters)
5. Visualized clusters using scatter plots

## Results
The analysis identified three user segments:
- Low engagement users
- Medium engagement users
- High engagement users

## Output
- Jupyter Notebook with analysis and clustering
- CSV file with cluster labels
