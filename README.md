# Customer Segmentation for ABCDEats Inc.

This repository contains the implementation of a data mining project developed for the Master’s in Data Science and Advanced Analytics at NOVA IMS. The objective was to assist ABCDEats Inc., a fictional food delivery platform, in identifying and understanding distinct customer segments through clustering techniques applied to behavioral, demographic, and transactional data.

**Academic Note**: This project received a final grade of 18.5 out of 20.

## Project Overview

ABCDEats Inc. partners with a variety of restaurants to offer diverse meal options to customers across three urban areas. To better tailor its marketing and operational strategies, the company seeks to segment its customer base using data collected over a three-month period.

The dataset includes information on customer demographics, order frequency and timing, cuisine preferences, vendor diversity, and promotion usage. The goal is to produce a segmentation model that captures meaningful differences in customer behavior and value, enabling data-driven decision-making.

## Objectives

- Conduct comprehensive exploratory data analysis (EDA) to identify trends, relationships, and anomalies.
- Engineer new features and preprocess the dataset to support unsupervised learning.
- Apply clustering algorithms and justify methodological decisions, including the number of clusters.
- Profile each cluster with descriptive analytics, incorporating multiple segmentation perspectives.
- Derive practical recommendations for ABCDEats to optimize marketing efforts and improve customer engagement.

## Methodology

The project follows a structured data mining pipeline:

1. **Data Exploration**: Summary statistics, visualizations, and feature correlations.
2. **Data Preprocessing**: Handling missing data, standardization, dimensionality reduction.
3. **Feature Engineering**: Aggregating temporal patterns (e.g., days of the week, hours of day), cuisine preferences, and recency/frequency metrics.
4. **Clustering**: Evaluation of multiple algorithms (e.g., K-Means, DBSCAN), selection of the optimal solution using internal validity metrics (e.g., silhouette score).
5. **Cluster Interpretation**: Analysis of cluster characteristics and their implications for business strategy.
6. **Recommendations**: Strategic suggestions for personalized marketing, loyalty programs, and customer retention initiatives.

## Tools and Technologies

- Python (NumPy, Pandas, Scikit-learn)
- Jupyter Notebooks
- Visualization libraries (Seaborn, Matplotlib)
- Clustering and evaluation techniques from unsupervised learning

## Dataset

The dataset consists of anonymized customer-level records, including:

- Demographic attributes (e.g., age, region)
- Behavioral data (e.g., order times by hour and day)
- Cuisine spending patterns
- Engagement indicators (e.g., first and last order, promotion use)


## Status

Project completed and submitted in January 2025 as part of the Data Mining course (DM2425). This repository includes all final materials used in the submission.
