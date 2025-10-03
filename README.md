# 🛍️ Customer Segmentation with RFM Analysis & K-Means Clustering  

## 📌 Project Overview  
This project analyzes an **e-commerce dataset** to segment customers and generate actionable business insights.  
We applied both **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering** to identify customer groups and provide recommendations for marketing and business strategy.  

👉 The aim is to combine **business intuition (RFM)** with **machine learning (K-Means)** for a balanced and data-driven segmentation approach.  

---

## 🛠️ Key Skills & Technologies  
- **Data Cleaning & Preprocessing** → handling missing values, duplicates, outliers.  
- **Exploratory Data Analysis (EDA)** → pandas, matplotlib, seaborn.  
- **Customer Segmentation** → RFM scoring & unsupervised clustering (K-Means).  
- **Evaluation & Business Interpretation** → comparing rule-based vs ML approaches.  
- **Storytelling with Data** → visuals & executive presentation.  

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## 📂 Repository Structure  

```text
customer-segmentation-rfm/
│
├── notebooks/
│   └── customer_segmentation_rfm.ipynb   # Full analysis notebook
├── slides/
│   └── Customer_Segmentation_Presentation.pdf   # Executive summary slides
├── data/   (optional - not shared if dataset is large/restricted)
└── README.md


---

## 📊 Methodology  
1. **Data Cleaning**  
   - Removed missing values, negative quantities, duplicates.  
   - Converted data types (dates, customer IDs).  

2. **RFM Analysis**  
   - Calculated Recency, Frequency, Monetary per customer.  
   - Applied segmentation rules: Champions, Loyal, At Risk, Lost.  

3. **K-Means Clustering**  
   - Standardized RFM values.  
   - Determined optimal clusters using the Elbow Method.  
   - Compared clustering vs RFM scoring.  

4. **Visualization & Insights**  
   - Histograms, scatter plots, revenue per segment.  
   - Highlighted differences between RFM vs K-Means results.  

---

## 💡 Key Insights  
- **Champions** → small group, highest individual spend → retention priority.  
- **Loyal Customers** → largest group, steady contributors → upsell opportunity.  
- **At Risk / Lost** → low spend, inactive → reactivation campaigns.  
- K-Means validated **3 main segments**, broadly aligning with RFM.  

---

## 🚀 Deliverables  
- 📓 [Jupyter Notebook](notebooks/customer_segmentation_rfm.ipynb) — full analysis  
- 📊 [Executive Summary Slides (PDF)](slides/Customer_Segmentation_Presentation.pdf) — business storytelling  
- 🗂️ GitHub repository with clean code & documentation  

---

## 📈 Business Recommendations  
- **Retain Champions** → loyalty programs, exclusive perks.  
- **Grow Loyal Customers** → targeted upsell/cross-sell.  
- **Recover At Risk/Lost** → reactivation offers & campaigns.  

---

## 📖 Next Steps  
- Automate segmentation pipeline for real-time dashboards.  
- Try advanced clustering (DBSCAN, hierarchical clustering).  
- Run A/B testing on campaigns for each customer group.  

---
