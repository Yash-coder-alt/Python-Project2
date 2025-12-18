# Python-Project 2 -- Mall CLustering
# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on **customer segmentation** using **K-Means Clustering** on a mall customers dataset.  
The goal is to group customers based on their **age, annual income, and spending behavior** so that businesses can better understand customer patterns and target them effectively.

The project includes:
- Exploratory Data Analysis (EDA)
- Univariate, Bivariate, and Multivariate analysis
- Clustering using the K-Means algorithm
- Optimal cluster selection using the Elbow Method
- Visualization of customer segments

---

## 📂 Dataset
**Mall_Customers.csv**

**Features used:**
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (KMeans)

---

## 📊 Exploratory Data Analysis
EDA is performed to understand customer distribution:
- Age distribution
- Annual income distribution
- Spending score distribution
- Relationship between income and spending

Univariate and bivariate visualizations help identify patterns before clustering.

---

## 🔍 Clustering Approach
### 1. Univariate Clustering
- Clustering customers based on **Annual Income**

### 2. Bivariate Clustering
- Clustering based on **Annual Income vs Spending Score**

### 3. Multivariate Clustering
- Clustering using **Age, Annual Income, and Spending Score**

---

## 📐 Elbow Method
The **Elbow Method** is used to find the optimal number of clusters by plotting inertia values and selecting the point where the curve bends.

---

## 📈 Results
- Customers are successfully segmented into meaningful groups
- Each cluster represents a distinct customer behavior
- Visual plots help clearly understand high spenders, low spenders, and average customers

---

## 🎯 Conclusion
This project demonstrates how unsupervised learning can be used for **customer segmentation**.  
The insights gained can help businesses in:
- Targeted marketing
- Personalized offers
- Customer relationship management

---

## 🚀 Future Improvements
- Apply other clustering algorithms (DBSCAN, Hierarchical Clustering)
- Add customer demographics
- Build a dashboard using Streamlit or Power BI
