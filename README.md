🧠 Task 8: Clustering with K-Means

📌 Objective

To understand and implement unsupervised learning using the **K-Means Clustering algorithm**. This task focuses on grouping customers based on similar behaviors using the **Mall Customer Segmentation Dataset**.



🛠️ Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (StandardScaler, KMeans, PCA, silhouette_score)



 📂 Dataset
 
Mall_Customers.csv

It includes customer features like:
- Age
- Annual Income (k$)
- Spending Score (1-100)

We removed `CustomerID` and `Gender` to focus on numeric data for clustering.



 📋 Steps Performed
 
 1. 📥 Data Loading & Preprocessing
- Loaded the CSV file.
- Dropped non-numeric columns (`CustomerID`, `Gender`).
- Standardized features using `StandardScaler`.

2. 📈 Elbow Method
- Plotted inertia values for different values of K (1 to 10).
- Found the optimal number of clusters using the **Elbow Method**.

3. 🤖 KMeans Clustering
- Applied KMeans with the chosen K.
- Assigned cluster labels to each data point.

4. 📊 Evaluation
- Evaluated clustering performance using **Silhouette Score**.

5. 🎨 Visualization
- Used **PCA** to reduce data to 2D.
- Visualized customer segments using scatter plot.


