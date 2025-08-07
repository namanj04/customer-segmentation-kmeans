# 🧠 Customer Segmentation using K-Means Clustering

This project segments mall customers into distinct groups using **K-Means Clustering**, an unsupervised machine learning technique. The clustering is based on key features like **Annual Income** and **Spending Score**, enabling businesses to better understand customer behavior and target them with personalized strategies.

---

## 🎯 Objective

- Segment customers based on behavior and financial attributes.
- Identify groups like high-spenders, budget buyers, impulsive customers, etc.
- Demonstrate real-world use of unsupervised ML in marketing analytics.

---

## 📁 Dataset

The dataset includes:
- `Customer ID` (removed during processing)
- `Gender` (excluded for clustering)
- `Age`
- `Annual Income`
- `Spending Score`

---

## ⚙️ Steps Performed

### ✅ 1. Data Preprocessing
- Dropped irrelevant columns
- Selected key numerical features: `Age`, `Annual Income`, `Spending Score`
- Scaled features using `StandardScaler`

### ✅ 2. Elbow Method
- Ran K-Means for `k = 1 to 10`
- Chose `k = 5` based on the elbow point in the inertia graph

### ✅ 3. K-Means Clustering
- Clustered customers into 5 segments
- Added cluster labels to the dataset

### ✅ 4. Visualization
- 2D scatter plot of `Annual Income` vs. `Spending Score` with color-coded clusters

---

## 📊 Cluster Insights

| Cluster | Income Level     | Spending Score | Segment Type                   |
|---------|------------------|----------------|--------------------------------|
| 0       | Low–Mid Income   | Low Spend      | 💤 Budget Buyers               |
| 1       | Low–Mid Income   | High Spend     | 💸 Impulsive Shoppers          |
| 2       | High Income      | Low Spend      | 🧊 Conservative Rich           |
| 3       | Mid Income       | Moderate Spend | 🛍️ Average Customers           |
| 4       | High Income      | High Spend     | 🔥 Premium/Loyal Customers     |

---

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

customer-segmentation-kmeans/
├── customer_segmentation.ipynb # Jupyter notebook with full code
├── mall_customer_data.csv # Dataset used
├── requirements.txt # Dependencies
└── README.md # Project overview and documentation

---

## 📬 Connect

Built as part of a Data Science Internship task.  
Feel free to reach out or collaborate on similar projects!

---

## #️⃣ Hashtags

`#CustomerSegmentation` `#KMeans` `#DataScience` `#MachineLearning` `#Clustering` `#UnsupervisedLearning` `#Python`
