# 🛍️ Customer Segmentation using Mall Customers Dataset

This project performs customer segmentation using unsupervised machine learning techniques on the **Mall Customers dataset**. The goal is to segment customers based on their behavior and demographics, which can help businesses improve marketing strategies and customer engagement.

## 📂 Dataset Overview

The dataset contains the following features:

- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Male or Female
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands
- `Spending Score (1-100)`: Score assigned based on customer behavior and spending patterns

📊 **Dataset Source**: [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## 🎯 Objective

To group similar customers into different segments based on their characteristics using clustering algorithms like **K-Means**. This segmentation can help in targeted marketing and customer relationship management.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Clustering and preprocessing

---

## 📌 Project Steps

### 1. Data Preprocessing
- Load dataset and check for nulls
- Encode categorical variables (Gender)
- Normalize/scale data (for clustering)

### 2. Exploratory Data Analysis (EDA)
- Distribution plots for features
- Correlation analysis
- Pairplots and heatmaps

### 3. Clustering (K-Means)
- Elbow Method to find optimal number of clusters (k)
- Fit K-Means algorithm
- Assign cluster labels to each customer

### 4. Visualization
- 2D scatter plot of clusters
- Cluster-wise customer characteristics
- Gender and age distribution in each cluster

---

## 📈 Results

- Identified **distinct customer segments** based on income and spending behavior.
- Clusters visualized in 2D to show separation.
- Insights drawn to help personalize marketing strategies for each group.

---

## 📌 Sample Insights

- **Cluster 1**: High income, high spenders – ideal for premium products.
- **Cluster 2**: Young customers with average income – potential for loyalty programs.
- **Cluster 3**: Low income, low spenders – budget marketing strategies.

---

## 📎 Files in Repository

| File | Description |
|------|-------------|
| `Mall_Customers.csv` | Original dataset |
| `customer_segmentation.ipynb` | Jupyter Notebook with code |
| `README.md` | Project overview |
| `segmentation_result.png` | Cluster visualization (optional) |

---

## 🚀 Future Work

- Try other clustering techniques (Hierarchical, DBSCAN)
- Integrate customer segmentation into a web dashboard
- Apply on real-time e-commerce data

---

## 🙌 Acknowledgments

Thanks to Kaggle and the contributors of the **Mall Customer Segmentation** dataset.

---

## 🧠 Author

Name: Bikkina Anusha 
Email: bikkinaanusha949@gmail.com
GitHub: Anusha949
---

## 📌 License

This project is licensed under the MIT License.

