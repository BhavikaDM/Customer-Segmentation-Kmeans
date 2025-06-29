# 🧠 Customer Segmentation Using K-Means Clustering

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to perform customer segmentation based on **Annual Income** and **Spending Score**.

### 📌 Objective

To group customers into distinct segments based on purchasing behavior, so that businesses can:

- Identify high-value customers
- Target marketing campaigns effectively
- Understand customer spending patterns

---

### 🗃️ Dataset

The dataset used is the **Mall Customer Segmentation Data** and includes the following features:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

### 📊 Features Used for Clustering

We selected the following two numerical features for clustering:

- **Annual Income (k$)**
- **Spending Score (1-100)**

These features effectively capture customer purchasing power and behavior.

---

## 🧪 Machine Learning Algorithm

### K-Means Clustering

- We used the **Elbow Method** to determine the optimal number of clusters.
- Cluster centroids were visualized.
- Customers were assigned to 5 clusters:

| Cluster | Description                           |
|---------|----------------------------------------|
| 0       | Medium Spend, Medium Income           |
| 1       | High Spend, High Income               |
| 2       | High Spend, Low Income                |
| 3       | Low Spend, High Income                |
| 4       | Low Spend, Low Income                 |

---

### 📈 Visualizations

- **Elbow Plot** to find optimal `K`
- **Scatter Plot** to visualize customer segments
- Centroids marked for each cluster

---

### 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation

   ```
### 📚 Learning Outcomes

- Applied unsupervised learning using K-Means

- Learned how to determine the optimal number of clusters

- Practiced real-world customer segmentation and visualization


### 📸 Sample Output

![Customer Segmentation Output](cluster_plot.png)

*Customer segments based on annual income and spending score.*
