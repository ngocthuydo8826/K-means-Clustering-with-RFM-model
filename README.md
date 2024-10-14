# K-means-Clustering-with-RFM-model

According to Xu, T. et al. (2023) "A novel telecom customer churn analysis system based on RFM model and feature importance ranking", Interdisciplinary Journal of Information, Knowledge, and Management (https://doi.org/10.28945/5192)
  - "In the telecom industry, most customers opt for monthly payments for their communication expenses, and thus the variable `Recency` is defined as the monthly payment, with a fixed value of 1 for all customers in this RFM model"
  - "Feature `Tenure in Months` describes how long a customer has been with the company, it is related to the variable `Frequency`"
  - "`Monthly Charges` attribute aligns with the monetary variable, as it reflects the customer’s value over a given period"

So I will take this research's results as RFM model parameters: `Recency` - `Monthly payments`, `Frequency` - `Tenure in Months`, `Monetary` - `Monthly charges`
- Using `Elbow Method` to find out the appropriate number of clusters: K=4 (4 clusters)
- And Python's library `scikit-learn`- Kmeans for scattering 4 clusters in plot

## Customer Segmentation with RFM model result
DATASET: R(mean)=1, F(mean)=32.39, M(mean)=64.76

(https://github.com/user-attachments/assets/f3ca2543-1e48-4dd3-adec-056884b69a8c)

- In cluster 1, F and M are lower than the average value so cluster  named `Less Consuming Short-Term Customers (LCSTC)`
- In cluster 2, F is higher than the average value, and M is lower than the average value, so cluster  named `Less Consuming Long-Term Customers (LCLTC)`
- In cluster 3, F and M are higher than the average value so cluster are named `High Consuming Long-Term Customers (HCLTC)`
- In cluster 4, F is lower than the average value of the dataset, and M is higher than the average value, so cluster named `High Consuming Short-Term Customers (HCSTC)`
