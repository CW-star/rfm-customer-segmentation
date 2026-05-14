# RFM Customer Segmentation

## Project Overview
An e-commerce company has 500K+ transactions but no idea which customers 
are Champions, which are At-Risk, and which are already Lost. This project 
builds a complete RFM (Recency, Frequency, Monetary) segmentation model using 
K-Means clustering to give the marketing team a precise, actionable customer map.

## Business Questions Answered
1. Who are our most valuable customers right now?
2. Which customers are showing early signs of churn?
3. How much revenue is concentrated in each segment?
4. Which segments should marketing prioritize for retention vs acquisition?

## Tools Used
- **Python** — pandas, scikit-learn, matplotlib, seaborn
- **K-Means Clustering** — unsupervised ML segmentation
- **RFM Scoring** — Recency, Frequency, Monetary value framework
- **Dataset** — UCI Online Retail (541,909 transactions, Kaggle)

## Segments Identified

| Segment | Customers | Revenue | Avg Spend | Last Purchase |
|---------|-----------|---------|-----------|---------------|
| Champions | 1,188 (20.2%) | $13.1M (73.7%) | $11,014 | 27 days ago |
| New / Promising | 1,251 (21.3%) | $1.1M (6.1%) | $865 | 28 days ago |
| At-Risk | 1,465 (24.9%) | $2.9M (16.5%) | $2,002 | 228 days ago |
| Lost / Inactive | 1,974 (33.6%) | $643K (3.6%) | $326 | 396 days ago |

## Key Finding
Champions are 20% of customers but drive 73.7% of revenue — $13.1M out of $17.7M total.
Losing one Champion costs more than acquiring 13 new customers.

## Status
✅ Complete — K-Means Clustering + RFM Scoring + 4 Python Visualizations


## Author
Cynthia Wanjiku Ng'ang'a | Business Analytics Graduate Student
https://www.linkedin.com/in/cynthia-ng%E2%80%99ang%E2%80%99a-b3b764350/
