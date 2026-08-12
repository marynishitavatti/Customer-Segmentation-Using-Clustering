📊 Customer Segmentation Using K-Means
📌 Project Overview

This project performs Customer Segmentation using the K-Means Clustering algorithm. It groups customers with similar characteristics into different clusters based on their Annual Income and Spending Score.

The objective is to understand customer behavior and provide actionable insights that can help businesses create targeted marketing strategies.

🎯 Objective
Segment customers into meaningful groups
Identify different customer behavior patterns
Analyze the relationship between annual income and spending score
Provide actionable business insights
Demonstrate the use of K-Means clustering for customer segmentation
📂 Dataset Details

The project uses the Mall Customers dataset.

Total Records: 200
Features: 5
Target: No predefined target variable
Missing Values: None
Dataset Features
CustomerID – Unique identifier for each customer
Gender – Customer gender
Age – Customer age
Annual Income (k$) – Annual income in thousands of dollars
Spending Score (1-100) – Score assigned based on customer spending behavior
Features Used for Clustering
Annual Income (k$)
Spending Score (1-100)

These two features were selected because they provide useful information about a customer's purchasing capacity and spending behavior.

🧹 Data Preparation

The following data preparation steps were performed:

Loaded the dataset using Pandas
Examined the dataset structure and data types
Checked for missing values
Performed basic exploratory data analysis
Selected Annual Income and Spending Score for clustering
🤖 Model Used
K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to divide data points into different clusters based on similarity.

In this project:

Number of clusters: 3
Algorithm: K-Means Clustering
Features: Annual Income and Spending Score

The model assigns each customer to one of the three clusters based on their similarity in income and spending behavior.

📊 Cluster Analysis

The K-Means model produced three customer segments:

Cluster 0 — Budget-shoppers
Customers: 38
Average Annual Income: 87.00 k$
Average Spending Score: 18.63

These customers have relatively high income but a low spending score.

Cluster 1 — High-spenders
Customers: 39
Average Annual Income: 86.54 k$
Average Spending Score: 82.13

These customers have relatively high income and high spending scores, making them an important segment for premium products and loyalty programs.

Cluster 2 — Occasional buyers
Customers: 123
Average Annual Income: 44.15 k$
Average Spending Score: 49.83

This is the largest customer segment, with a moderate spending pattern.

🔍 Key Insights
High-spenders have both high income and high spending scores.
Budget-shoppers have high income but comparatively low spending scores.
Occasional buyers form the largest customer segment.
Annual income alone does not determine spending behavior.
Different customer groups show distinct purchasing patterns.
💼 Business Recommendations

Based on the customer segments, businesses can use different strategies for each group:

Offer premium products and loyalty rewards to High-spenders.
Use targeted discounts and promotional offers for Budget-shoppers.
Create engagement and seasonal campaigns for Occasional buyers.
Personalize marketing strategies according to customer behavior.
Use customer segmentation to improve customer engagement and marketing effectiveness.


🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook


🚀 Project Workflow
Data Collection
Data Loading
Data Exploration
Data Cleaning
Feature Selection
K-Means Model Training
Customer Clustering
Cluster Analysis
Business Insight Generation
Customer Segmentation Recommendations


📈 Project Output

The project successfully grouped customers into three meaningful segments based on Annual Income and Spending Score:

Cluster	Customer Segment	Customers
0	Budget-shoppers	38
1	High-spenders	39
2	Occasional buyers	123

The clustering results can be used by businesses to understand customer behavior and develop more targeted marketing strategies.

📁 Repository Contents
Customer-Segmentation-Using-Clustering/
│
├── Customer_Segmentation_using_Clustering.ipynb
├── Mall_Customers.csv
├── Customer_Segmentation_Project_Ppt.pptx
└── README.md
👨‍💻 Author

Mary Nishita Vatti
