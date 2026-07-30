# Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview

This project focuses on customer segmentation using **Unsupervised Machine Learning** techniques. The objective is to identify hidden groups of customers based on their demographic information and purchasing behavior.

The project uses **Principal Component Analysis (PCA)** for dimensionality reduction and **K-Means Clustering** to group customers with similar characteristics. The **Elbow Method** and **Silhouette Score** are used to determine the optimal number of clusters.

The identified customer segments help businesses understand customer behavior and support data-driven marketing strategies.

---

## 🎯 Objectives

- Explore and understand the customer dataset.
- Clean and preprocess the data.
- Handle missing values.
- Encode categorical variables.
- Scale numerical features.
- Apply Principal Component Analysis (PCA).
- Determine the optimal number of clusters using the Elbow Method.
- Evaluate clustering quality using the Silhouette Score.
- Build customer segments using K-Means clustering.
- Analyze and interpret customer personas.

---

## 📂 Dataset

The project uses the **Customer Personality Analysis** dataset, which contains customer demographic information, household details, and purchasing behavior.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading
The dataset is loaded into a Pandas DataFrame for analysis.

### 2. Data Preprocessing
The data is cleaned by handling missing values, removing unnecessary columns, and encoding categorical features into numerical values.

### 3. Feature Scaling
StandardScaler is applied to standardize the features before clustering.

### 4. Dimensionality Reduction (PCA)
Principal Component Analysis (PCA) is used to reduce the number of features while preserving most of the important information.

### 5. Elbow Method
The Elbow Method is used to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

### 6. Silhouette Score
Silhouette Score is calculated to evaluate how well the clusters are separated.

### 7. K-Means Clustering
K-Means clustering groups customers into different clusters based on their similarities.

### 8. Cluster Visualization
The generated clusters are visualized using the first two principal components obtained from PCA.

### 9. Customer Persona Analysis
Each cluster is analyzed to create meaningful customer personas that can support business decision-making.

---

## 📊 Evaluation Techniques

- Principal Component Analysis (PCA)
- Elbow Method
- Silhouette Score
- K-Means Clustering
- Cluster Visualization

---

## 📈 Results

The project successfully identified multiple customer segments based on purchasing behavior and demographic characteristics.

The generated customer groups can be used for:

- Targeted Marketing
- Personalized Product Recommendations
- Customer Retention Strategies
- Loyalty Programs
- Business Intelligence
- Customer Behavior Analysis

---

## 👩‍💻 Author

### Zainab Sarfraz

