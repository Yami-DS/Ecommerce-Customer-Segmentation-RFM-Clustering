# Ecommerce Customer Segmentation using RFM Analysis
🏷️ Project Title:

Customer Segmentation using RFM Analysis & Clustering

🎯 Objective:

The objective of this project is to draw meaningful insights from e-commerce transaction data by performing RFM (Recency, Frequency, Monetary) analysis and applying clustering techniques to segment customers based on their purchasing behavior.
This helps businesses target the right customers with personalized marketing strategies.

📊 Project Overview:

In this project, I explored an E-Commerce dataset to identify customer patterns and behaviors.
By calculating RFM metrics, I clustered customers into meaningful groups such as:

🏆 Platinum

💰 Diamond

💤 Gold

🌱 Silver

I used K-Means Clustering and Visualization techniques to understand these segments better.

🧩 Steps Involved:

Data Understanding & Cleaning

Handling missing values and duplicates

Filtering valid transactions (e.g., positive quantities)

Feature Engineering (RFM Metrics)

Recency – Days since the last purchase

Frequency – Number of transactions

Monetary – Total spend amount

Data Standardization

Scaled RFM values for better clustering performance

Model Building (Clustering)

Used K-Means Clustering

Determined optimal clusters using Elbow Method & Silhouette Score

Visualization & Insights

Visualized clusters using Matplotlib and Seaborn

Interpreted each segment with actionable insights

🧠 Key Insights:

Identified 4 major customer groups with distinct spending behaviors.

Top 20% of customers contributed to ~70% of revenue (Pareto Principle observed).

High-value customers made frequent purchases with low recency.

Inactive customers formed the largest group — ideal for re-engagement campaigns.

🛠️ Tech Stack:

Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Algorithm: K-Means Clustering

Data Visualization: Matplotlib, Seaborn

Data Source: E-Commerce sales dataset (can be from Kaggle / simulated)
