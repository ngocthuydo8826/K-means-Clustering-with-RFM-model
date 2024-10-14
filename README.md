# K-means-Clustering-with-RFM-model

According to Xu, T. et al. (2023) "A novel telecom customer churn analysis system based on RFM model and feature importance ranking", Interdisciplinary Journal of Information, Knowledge, and Management (https://doi.org/10.28945/5192)
  - "In the telecom industry, most customers opt for monthly payments for their communication expenses, and thus the variable `Recency` is defined as the monthly payment, with a fixed value of 1 for all customers in this RFM model"
  - "Feature `Tenure in Months` describes how long a customer has been with the company, it is related to the variable `Frequency`"
  - "`MonthlyCharges` attribute aligns with the monetary variable, as it reflects the customer’s value over a given period"

So I will take this research's results as RFM model parameters: `Recency` - `Monthly payments`, `Frequency` - `Tenure in Months`, `Monetary` - `Monthly charges`
- Using `Elbow Method` to find out the appropriate number of clusters: K=4 (4 clusters)
- And Python's library `scikit-learn`- Kmeans for scattering 4 clusters in plot

## Customer Segmentation with RFM model result

![Screenshot_14-10-2024_71526_](https://github.com/user-attachments/assets/f3ca2543-1e48-4dd3-adec-056884b69a8c)
