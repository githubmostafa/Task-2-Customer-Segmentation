Customer Segmentation using KMeans and DBSCAN
This project applies clustering algorithms (KMeans and DBSCAN) to group mall customers based on their Annual Income and Spending Score. It is a simple yet effective use case of unsupervised learning in real-world marketing analytics.

Objective
Segment customers into distinct groups to help the marketing team design targeted campaigns and better understand customer behavior.

Project Structure

Data Used
The Mall_Customers dataset (from Kaggle) was used. It includes information about mall customers such as:

Customer ID

Gender

Age

Annual Income (in dollars)

Spending Score (1 to 100)

Data Preprocessing

Checked for null values and verified data types

Visualized feature distributions (Age, Income, Spending Score)

Selected relevant features: Annual Income and Spending Score

Applied StandardScaler to prepare data for DBSCAN

KMeans Clustering

Used the Elbow Method to determine the optimal number of clusters (k = 5)

Performed clustering and labeled the groups

Visualized cluster results with centroids

Stored cluster labels in the DataFrame

DBSCAN Clustering (Bonus)

Applied DBSCAN with eps = 0.5 and min_samples = 5

Automatically detected outliers

Compared DBSCAN results with KMeans clustering

Calculated the average spending score per cluster

Visualizations

Histograms for Age, Annual Income, and Spending Score

Scatter plot of Income vs Spending Score colored by Gender

Elbow Method plot to determine optimal k

KMeans cluster visualization with centroids

DBSCAN cluster visualization highlighting outliers

Technologies Used

Python (pandas, matplotlib, seaborn, scikit-learn)

Jupyter Notebook

GitHub

Conclusion
This analysis helped identify valuable customer segments such as:

High income and high spending customers

Low income and high spending customers

Outliers using DBSCAN

These insights support personalized marketing efforts and improved customer retention strategies.

