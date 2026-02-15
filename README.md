[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sid9397/customer-segmentation-kmeans/blob/main/customer_segmentation_kmeans.ipynb)

# 📊 Customer Segmentation using K-Means Clustering

---

## 🎯 Business Objective
A retail company wants to segment customers based on income and spending behavior to improve marketing strategy and customer targeting.

---

## 🧠 Methodology

The project follows an industry-standard clustering workflow:

- Data preprocessing & scaling
- Optimal cluster selection using:
  - Elbow Method
  - Silhouette Score
- Model training using **K-Means++**
- Model evaluation using:
  - Silhouette Score
  - Davies–Bouldin Index
  - Calinski–Harabasz Score
- Cluster profiling using group statistics
- Stability validation
- Business interpretation

---

## ⚙️ Model Evaluation

| Metric | Value |
|-------|------|
| Silhouette Score | 0.331 |
| Davies-Bouldin Index | 1.017 |
| Calinski-Harabasz Score | 73.49 |

These metrics indicate reasonably separated and compact customer clusters.

---

## 👥 Customer Segments Identified

| Cluster Type | Description |
|-------------|-------------|
| Premium Customers | High income, high spending |
| Wealthy Savers | High income, low spending |
| Target Customers | Medium income, high spending |
| Budget Active Buyers | Low income, high spending |
| Average Customers | Moderate income & spending |

---

## 💼 Business Insights

✅ Focus marketing campaigns on **Wealthy Savers** to increase engagement  
✅ Maintain loyalty programs for **Premium Customers**  
✅ Avoid aggressive promotion toward **low-income high-spenders** (ethical targeting)  
✅ Maintain standard engagement for average customers  

---

## 📈 Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- KMeans++

---

## 🚀 Key Learning Outcomes

- Practical unsupervised learning workflow
- Cluster validation techniques
- Data-driven customer strategy building
