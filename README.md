📊 Customer Segmentation using RFM Analysis & K-Means Clustering
📌 Project Overview

This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) framework combined with K-Means clustering.
The goal is to analyze customer purchasing behavior and group customers into meaningful segments that can be used for targeted marketing and retention strategies.

The dataset contains three years of retail sales transaction data.

🧠 Problem Statement

Businesses often struggle to identify:

Their most valuable customers

Customers at risk of churn

New or low-engagement customers

This project addresses this problem by segmenting customers based on their transaction history.

🗂 Dataset

Source: Kaggle – Sample Sales Data

Time Period: 3 years

Data Type: Retail transaction data

⚙️ Methodology
1️⃣ Data Cleaning & Preparation

Removed irrelevant columns

Converted order dates to datetime format

Aggregated transactional data at the customer level

2️⃣ RFM Analysis

Recency: Days since last purchase

Frequency: Total number of purchases

Monetary: Total amount spent

Converted RFM values into quartile-based scores (0–3)

3️⃣ Clustering

Applied K-Means clustering on RFM scores

Used the Elbow Method to determine optimal number of clusters

Selected 4 customer segments

👥 Customer Segments Identified

Active – High-value, frequent, and recent customers

New – Recently acquired customers with low history

Departing – Previously valuable customers with declining activity

Inactive – Low engagement and low spending customers

📈 Visualizations

Sales distribution and trend plots

Elbow plot for cluster selection

3D scatter plots for customer clusters

📂 Final Output

Generated a CSV file containing customer segments

Each customer is labeled as Active, New, Departing, or Inactive

Sample Output (Customer Segmentation)

(Insert your screenshot here)

CUSTOMERNAME | Recency | Frequency | MonetaryValue | SegmentName

 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook / VS Code

💡 Business Insights

Helps identify high-value customers for loyalty programs

Supports re-engagement strategies for at-risk customers

Enables data-driven marketing decisions