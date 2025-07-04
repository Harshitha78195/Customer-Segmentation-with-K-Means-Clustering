# Customer Segmentation with K-Means Clustering

##  Overview
This project demonstrates unsupervised learning using **K-Means Clustering** to segment customers based on features such as **Age**, **Gender**, **Annual Income**, and **Spending Score**. It includes evaluation techniques like the **Elbow Method** and **Silhouette Score** for optimal cluster selection and performance validation.

---

##  Tools Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn (optional)
- PCA (for dimensionality reduction)

---

##  File Structure

├── KMeans_Customer_Segmentation.ipynb # Main Jupyter notebook

├── Mall_Customers.csv # Dataset file (or replace with actual dataset name)

└── README.md # Project documentation


---

##  Task Objectives
- Load and preprocess the customer dataset
- Convert categorical features (like Gender) to numeric
- Visualize data distribution (optional)
- Apply **K-Means clustering** to group customers
- Use **Elbow Method** to determine optimal number of clusters (K)
- Use **Silhouette Score** to evaluate clustering performance
- Visualize clusters (including 2D PCA view)

---

##  Evaluation Metrics
- **Inertia** (used in Elbow Method)
- **Silhouette Score**
- **Cluster visualization** using Matplotlib (optionally PCA for 2D reduction)

---

##  Silhouette Score
Silhouette Score helps assess how well-defined the clusters are. In this project, the best Silhouette Score was observed at **K = 5**, indicating that dividing the customers into 5 groups yields the best separation.

---

##  Elbow Method
The Elbow plot visualizes how inertia decreases with increasing K. A noticeable "elbow" in the plot indicates the ideal value of K for clustering.

---

##  How to Run
1. Clone this repository or download the `.ipynb` and dataset files.
2. Make sure the dataset (e.g., `customers.csv`) is in the same directory.
3. Open the notebook: `KMeans_Customer_Segmentation.ipynb`.
4. Run all cells in order to:
   - Load and preprocess the data
   - Run KMeans clustering
   - Evaluate and visualize results

---

##  What You’ll Learn
- Basics of **unsupervised learning** with K-Means
- Data preprocessing and label encoding
- How to choose the **optimal number of clusters**
- Evaluating clusters with **Silhouette Score**
- Visualizing high-dimensional clusters using **PCA**
- Real-world applications of customer segmentation in marketing

---

##  Dataset
**Mall Customers Dataset**  
- Format: CSV file with columns like `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`
- You can find similar datasets on [Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial) or use your own.

---

##  Use Case
Businesses can use this clustering technique to segment customers and:
- Create targeted marketing campaigns
- Optimize customer experience
- Increase ROI on personalized offers

---

##  Sample Result
The clustering model grouped the customers into **5 segments** with a Silhouette Score of **~0.44**, indicating well-separated and meaningful groupings.

---




