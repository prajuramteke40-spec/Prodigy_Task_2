# Prodigy Infotech: Machine Learning - Task 02

## 🛍️ Customer Segmentation using K-Means Clustering

This repository contains the implementation of Task 02 for the Prodigy Infotech Machine Learning Internship. The objective of this project is to create a K-means clustering algorithm to group customers of a retail store based on their purchase history, specifically focusing on their annual income and spending score.

### 📋 Project Overview
Customer segmentation is a powerful technique used by businesses to divide their customer base into distinct groups that share similar characteristics. In this project, we apply the **K-Means Clustering** algorithm to a Mall Customers dataset. By clustering customers based on their Annual Income and Spending Score, the store can identify target audiences for marketing strategies and better understand customer behavior.

To make the code easily reproducible, the dataset is loaded directly from a raw GitHub URL within the script, eliminating the need for manual downloads.

### 🛠️ Technologies & Libraries Used
* **Python 3.x:** Core programming language.
* **Pandas & NumPy:** For data ingestion, manipulation, and array operations.
* **Scikit-Learn:** For implementing the K-Means clustering algorithm.
* **Matplotlib & Seaborn:** For plotting the Elbow curve and visualizing the final customer clusters.

### 🧠 Methodology
1. **Data Loading:** The dataset is imported directly via URL.
2. **Feature Selection:** We extract a 2D feature matrix using the `Annual Income (k$)` and `Spending Score (1-100)` columns.
3. **Finding Optimal 'K':** We use the **Elbow Method** to determine the ideal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against different values of K. 
4. **Model Training:** Based on the Elbow graph, the optimal number of clusters (K=5) is selected, and the K-Means model is trained.
5. **Visualization:** The final clusters and their respective centroids are plotted on a 2D scatter graph.

### 📊 Results & Visualizations
The model successfully grouped the data into 5 distinct customer segments. 

**1. Determining K (The Elbow Method):**
The graph below demonstrates the Elbow Method. The curve bends or "elbows" at `K=5`, indicating that 5 is the optimal number of clusters for this dataset.

**2. Customer Clusters:**


### 🚀 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/prajuramteke40-spec/Prodigy_Task_2.git)
