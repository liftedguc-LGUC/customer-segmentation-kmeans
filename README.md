# 🛒 Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project uses **Unsupervised Machine Learning** to segment customers based on their demographic and purchasing behavior.

The project applies the **K-Means Clustering algorithm** to identify groups of customers with similar characteristics.

The objective is to help businesses understand customer behavior and design targeted marketing strategies.

---

## 🎯 Objectives

- Analyze customer behavior
- Identify customer segments
- Determine the optimal number of clusters
- Apply K-Means clustering
- Evaluate clusters using Silhouette Score
- Visualize clusters using PCA
- Generate business insights from customer segments

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- PCA

---

## 📊 Features Used

The clustering model uses the following customer features:

- Age
- Annual Income
- Spending Score
- Purchase Frequency
- Average Order Value
- Website Visits
- Discount Usage

---

## 🔄 Project Workflow

```text
Customer Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Selection
       ↓
Feature Scaling
       ↓
Elbow Method
       ↓
Silhouette Score
       ↓
K-Means Clustering
       ↓
Cluster Analysis
       ↓
PCA Visualization
       ↓
Customer Segmentation
       ↓
Business Recommendations
```

---

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters.

The algorithm works by:

1. Selecting the number of clusters
2. Initializing cluster centroids
3. Assigning customers to the nearest centroid
4. Recalculating centroids
5. Repeating until the clusters stabilize

---

## 📈 Model Evaluation

Two techniques are used to determine the appropriate number of clusters:

### Elbow Method

The Elbow Method uses **inertia** to determine an appropriate value of K.

### Silhouette Score

The Silhouette Score evaluates how well-separated the clusters are.

A higher score generally indicates better-defined clusters.

---

## 📉 PCA Visualization

Principal Component Analysis (PCA) is used to reduce the dimensionality of the customer data so that the clusters can be visualized in two dimensions.

---

## 📁 Project Structure

```text
customer-segmentation-kmeans/
│
├── customer_segmentation.py
├── customer_segments.csv
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd customer-segmentation-kmeans
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the project

```bash
python customer_segmentation.py
```

---

## 💡 Business Applications

Customer segmentation can be used for:

- Personalized marketing
- Customer retention
- Targeted promotions
- Loyalty programs
- Premium customer identification
- Discount campaigns
- Customer behavior analysis

---

## 🚀 Future Improvements

- Use a real-world customer dataset
- Add an interactive Streamlit dashboard
- Add automated customer segment descriptions
- Compare K-Means with DBSCAN and Hierarchical Clustering
- Deploy the project as a web application

---

## 👩‍💻 Author

**Lifted**

Python | Data Science | Machine Learning | AI Trainer
