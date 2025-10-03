# Customer Segmentation using RFM Analysis

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 📁 Repository Structure

```
customer-segmentation-rfm/
│
├── notebooks/
│   └── customer_segmentation_rfm.ipynb    # Full analysis notebook
│
├── slides/
│   └── Customer_Segmentation_Presentation.pdf    # Executive summary slides
│
├── data/    
│
└── README.md
```

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

## 📖 Next Steps (Optional)

- Automate segmentation pipeline for real-time dashboards.
- Try advanced clustering (DBSCAN, hierarchical clustering).
- Run A/B testing on campaigns for each customer group.

---

## 👤 Author

Omar Saqr(https://github.com/Omarsaqr)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
