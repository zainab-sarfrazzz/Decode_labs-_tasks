# Project 3: Customer Segmentation Using Unsupervised Learning

## Project Overview

This project focuses on customer segmentation using Unsupervised Learning techniques. The goal is to discover hidden groups of customers based on their demographic and purchasing behavior.

PCA is used for dimensionality reduction, while K-Means clustering is used to group similar customers. The Elbow Method and Silhouette Score are used to find the suitable number of clusters.

## Objectives

- Clean and preprocess customer data
- Handle missing values
- Encode categorical features
- Scale the data
- Apply Principal Component Analysis (PCA)
- Use the Elbow Method to find the optimal number of clusters
- Use Silhouette Score to evaluate clustering quality
- Apply K-Means clustering
- Visualize customer segments
- Create meaningful customer personas

## Dataset

The project uses the Customer Personality Analysis dataset. The dataset contains information about customer demographics, household details, and purchasing behavior.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Methodology

### 1. Data Preprocessing

The dataset is cleaned and prepared for analysis. The Customer ID is removed because it does not provide useful information for clustering. Missing values are handled, and categorical features are converted into numerical form.

### 2. Feature Scaling

StandardScaler is used to scale the features so that all variables have a similar range. This is important because K-Means clustering is based on distance calculations.

### 3. Principal Component Analysis (PCA)

PCA is applied to reduce the dimensionality of the dataset while preserving most of the important information.

### 4. Elbow Method

The Elbow Method is used to evaluate different numbers of clusters. The WCSS (Within-Cluster Sum of Squares) values are calculated for different values of K.

### 5. Silhouette Score

The Silhouette Score is used to measure how well-separated the clusters are. A higher score indicates better-defined clusters.

### 6. K-Means Clustering

K-Means clustering is applied using the selected number of clusters. Each customer is assigned to a cluster based on similarities in their characteristics and purchasing behavior.

### 7. Customer Personas

The resulting clusters are analyzed and translated into meaningful customer personas. These personas can help businesses understand customer behavior and create targeted marketing strategies.

## Results

The project identifies different customer segments based on their characteristics and purchasing behavior. PCA visualization is used to display the clusters, while cluster profiling helps understand the differences between customer groups.

The identified customer segments can be used for:

- Targeted marketing
- Personalized offers
- Customer retention
- Loyalty programs
- Better business decision-making
