Customer Segmentation with RFM Analysis & K-Means Clustering
📌 Project Overview

This project analyzes an e-commerce dataset to segment customers and generate actionable business insights. Using both RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, we identify different customer groups and provide recommendations for marketing and business strategy.

The goal is to combine business intuition (RFM) with machine learning (K-Means) for a balanced and data-driven segmentation approach.

🛠️ Key Skills & Technologies

Data Cleaning & Preprocessing: handling missing values, duplicates, outliers.

Exploratory Data Analysis (EDA): using pandas, matplotlib, and seaborn.

Customer Segmentation: RFM scoring and unsupervised clustering (K-Means).

Evaluation & Business Interpretation: comparing rule-based vs machine learning approaches.

Storytelling with Data: summarizing insights for business stakeholders.

Tech Stack: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

📂 Repository Structure
customer-segmentation-rfm/
│
├── notebooks/
│   └── customer_segmentation_rfm.ipynb   # Full analysis notebook
├── slides/
│   └── Customer_Segmentation_Presentation.pdf   # Executive summary slides
├── data/   (optional - not shared if dataset is large/restricted)
└── README.md

📊 Methodology

Data Cleaning

Removed missing values, negative quantities, duplicates.

Converted data types (e.g., dates, customer IDs).

RFM Analysis

Calculated Recency, Frequency, Monetary metrics per customer.

Applied scoring and segmentation rules (Champions, Loyal, At Risk, Lost).

K-Means Clustering

Standardized RFM values.

Determined optimal clusters using the Elbow Method.

Compared clustering results with RFM scoring.

Visualization & Insights

Histograms, scatter plots, revenue per segment.

Highlighted differences between RFM vs K-Means findings.

💡 Key Insights

Champions: small group, high individual spend — retention priority.

Loyal Customers: largest group, steady contributors — upsell opportunity.

At Risk / Lost: low spend, long inactivity — potential reactivation campaigns.

K-Means clustering validated the existence of 3 key segments, aligning broadly with RFM rules.

🚀 Deliverables

Jupyter Notebook
 with full analysis

Executive Summary Slides (PDF)

GitHub repository with clean code and documentation

📈 Business Recommendations

Champions → VIP programs, exclusive offers to retain them.

Loyal Customers → targeted upsell/cross-sell strategies.

At Risk/Lost → reactivation discounts, personalized outreach.

📖 Next Steps (Optional Extensions)

Automate segmentation pipeline for real-time dashboards.

Apply advanced clustering (DBSCAN, hierarchical clustering).

Perform A/B testing on marketing campaigns per segment.
