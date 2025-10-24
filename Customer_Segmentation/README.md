⚙️ Methodology
1. Data Preparation

Cleaned and preprocessed 430K+ transactional records from UK and non-UK markets.

Removed duplicates, handled missing values, and converted date/time formats for consistency.

2. Feature Engineering

Calculated RFM metrics for each customer:

Recency – days since last purchase

Frequency – total number of transactions

Monetary – total spending amount

Scaled features using MinMaxScaler for clustering.

3. Modeling (K-Means Clustering)

Determined the optimal number of clusters (k=3) using the elbow and silhouette methods.

Applied K-Means clustering to segment customers into behavior-based groups.

4. Evaluation & Visualization

Visualized clusters using 2D PCA plots and RFM distribution charts.

Compared average RFM scores across clusters to interpret business meaning.

💡 Key Insights

Cluster 1 – High-Value Customers: frequent buyers with high monetary value and short recency; ideal for loyalty campaigns.

Cluster 2 – Potential Loyalists: moderate spending but stable repeat purchases; suitable for engagement incentives.

Cluster 3 – At-Risk Customers: long recency and low frequency; require reactivation strategies.

Non-UK customers showed higher engagement, suggesting regional differences in retention behavior.

🧰 Tools & Technologies

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Techniques: RFM Analysis, Feature Scaling, K-Means Clustering, Data Visualization

📊 Business Impact

Provides actionable segmentation for targeted marketing campaigns and customer lifetime value management.

Supports data-driven decision-making in retention strategy and performance tracking.

Framework can be adapted for other industries requiring behavioral customer insights.