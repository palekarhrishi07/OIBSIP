# Customer Segmentation – OIBSIP Internship

## Objective
Segment customers into groups using K-Means clustering to inform targeted marketing.

## Dataset
ifood_df.csv (marketing analytics dataset provided in internship PDF)

## Steps performed
1. Loaded data and removed irrelevant columns (Z_CostContact, Z_Revenue).
2. Performed basic cleaning and no-missing check.
3. Selected behavioral and demographic numeric features (Income, Age, MntTotal, NumWebPurchases, etc.).
4. Scaled features with StandardScaler.
5. Determined optimal k using Elbow and Silhouette methods.
6. Applied K-Means and visualized clusters using PCA.
7. Analyzed cluster profiles and business metrics (Response, AcceptedCmpOverall, Complain).
8. Saved segmented dataset: `segmented_customers.csv`.

## Files
- customer_segmentation.ipynb
- raw_customers.csv
- segmented_customers.csv
- cluster_summary.csv

