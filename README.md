# Customer Segmentation Analysis

K-Means clustering on e-commerce customer data (2,205 customers, 39 features) to identify segments for targeted marketing.

## Methodology
1. Explore and clean data
2. Select 13 behavioral features (income, spending, channels, campaigns, demographics)
3. Scale with StandardScaler
4. Find optimal k using Elbow Method and Silhouette Score
5. Fit K-Means with k=4
6. Visualize with PCA, scatter plot, and heatmap
7. Profile segments and recommend strategies

## Insights
4 balanced segments identified.   
PCA explains 56.57% of variance in 2D. High-Value Loyalists spend about 12 times more than the lowest segment.   
Campaign acceptance correlates with income and spend. k=4 was chosen over k=2 for better business interpretability.  

## Recommendations
High-Value Loyalists: VIP program and exclusive access.
Budget Families: bundle discounts and deal alerts.
Mid-Spenders: cross-sell offers and app personalization.
Low-Engagement Young: first-purchase discounts and social media campaigns.

## How to Run
pip install pandas numpy matplotlib seaborn scikit-learn  
Run customer_segmentation.ipynb in Jupyter Notebook

## Tools
Python, pandas, scikit-learn, matplotlib, seaborn
