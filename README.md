# 🧮 Customer Lifetime Value Prediction (CLTV)

This project focuses on predicting customer lifetime value using historical transaction data. By combining **RFM segmentation** and **probabilistic models**, businesses can forecast customer purchase behavior, prioritize retention efforts, and maximize long-term revenue.

---

## 🚀 Objective

To build a model that estimates the expected number of future purchases by each customer, enabling data-driven strategies for customer targeting, budgeting, and personalized marketing.

---

## 🔍 Methodology & Business Impact

This end-to-end pipeline enables businesses to:

- **Segment customers** using RFM (Recency, Frequency, Monetary) analysis to identify high-value vs. at-risk customers.
- **Predict customer behavior** using probabilistic models: `BG-NBD`, `Pareto-NBD`, and `MBG-NBD`.
- **Visualize customer trends** using Frequency-Recency matrices, expected purchase plots, and model performance comparisons.
- **Make smarter decisions** with data-driven insights into customer value, retention strategies, and lifetime revenue forecasting.

By identifying which customers are most likely to make repeat purchases, companies can invest in personalized offers, loyalty campaigns, and retention strategies where they matter most.

---

## 📊 Models Used

| Model        | MSE Purchase Error | RMSE Purchase Error | Avg Purchase Error |
|--------------|--------------------|----------------------|---------------------|
| **BG-NBD**   | 4.051991           | 2.012956             | 0.409305            |
| **Pareto-NBD** | 4.039627         | 2.009882             | 0.409597            |
| **MBG-NBD**  | 4.051991           | 2.012956             | 0.409305            |

✅ **Pareto-NBD** gave the most accurate prediction across all metrics.

---

## 📈 Visual Insights

- Frequency vs. Recency Matrix  
- Expected Purchase Charts  
- Model Fit Comparisons  
- CLTV Distribution Plots

> These visuals provide a clear understanding of model effectiveness and customer patterns, even for non-technical stakeholders.

---

## 🧰 Tech Stack

- Python
- SQL
- Lifetimes (for probabilistic models)
- Matplotlib, Seaborn
- Jupyter Notebook

---
