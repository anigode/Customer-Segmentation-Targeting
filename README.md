# Customer-Segmentation-Targeting
- Table of Contents
- Business Problem
- Objective
- Introduction
- Installation
- Usage
- Data
- Analysis
- Evaluation
- Libraries
- Tools

# Business Problem
A retail company wants to better understand its customers to improve marketing effectiveness and increase revenue. The business requires:
- Segmentation of customers based on purchasing behavior and demographics
- Identification of high-value and low-value customer groups
- Actionable targeting strategies for marketing campaigns

# Objective
- Segment customers into meaningful groups using clustering algorithms (K-Means, Hierarchical Clustering)
- Profile customer clusters based on spending, frequency, and demographics
- Identify opportunities for targeted marketing and cross-selling
- Export enriched datasets for visualization in Power BI or Tableau

# Introduction
This project applies unsupervised machine learning to segment customers based on features such as purchase history, frequency, recency, monetary value, and demographics.
The outcome is a cluster assignment for each customer, enabling businesses to tailor marketing strategies and prioritize high-value segments.

# Installation
- Clone the repository
- Install required Python libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
- Open the Jupyter notebook
- Load the dataset (Mall_Customers.csv)
- Run all preprocessing, clustering, and visualization cells

Usage
- Load the dataset and perform exploratory data analysis
- Preprocess numerical and categorical features
- Apply clustering algorithms (K-Means, Hierarchical Clustering)
- Profile clusters by demographic and spending attributes
- Export enriched dataset (clustered_customers.csv)
- Visualize clusters in Power BI or Tableau for actionable insights

# Data
- Dataset size: 200–500 customers (depending on dataset)
- Key features:
  - Customer ID
  - Gender
  - Age
  - Annual Income
  - Spending Score
  - Cluster assignment (after modeling)

# Analysis
- Customer distribution by age, gender, and income
- Spending Score segmentation
- Clustering analysis:
  - K-Means elbow method for optimal clusters
  - Silhouette score for cluster quality
- Cluster profiling:
  - High spenders
  - Young frequent buyers
  - Low-value occasional customers

# Evaluation
- Model Performance Metrics:
  - | Model | Metric | Value |
  - | K-Means | Silhouette Score | 0.55 |
  - | Hierarchical | Dendrogram Consistency | High |

- Business Recommendations:
  - Target high-spending, frequent buyers with loyalty programs
  - Offer promotions to low-value clusters to increase engagement
  - Customize marketing campaigns for each cluster to maximize ROI

# Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

# Tools
- Jupyter Notebook
- Power BI / Tableau (for visualization)
- Git & GitHub
