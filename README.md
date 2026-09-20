SOME INTERESTING OBSERVATIONS

1. Extreme skewness still exists even after preprocessing, the mean values of CustAccountBalance and TransactionAmount (INR)
remained much higher than their medians across all clusters. This showed me how strongly a small number of extreme values can affect statistical summaries.
For understanding the “typical” customer, the median was much more useful than the mean.

2. Age barely differentiated the clusters: The median age across all four segments was between 27 and 29 years.
So, in this dataset, age did not appear to be a major factor separating customer financial behavior.

3. Cluster 1 — This segment had the highest median account balance and the highest median transaction amount. 
Median balance: ₹24,971.63
Median transaction: ₹557.05

4. Cluster 0 — This group had the lowest median balance and the lowest median transaction amount.
Median balance: ₹12,280.43
Median transaction: ₹349.50

5. Cluster 2 — This one was particularly interesting. It had the highest mean account balance overall,
while its median balance was also the second highest. At the same time, its transaction amounts were relatively low.
That suggests a segment with comparatively more money available but lower transaction activity.

6. Cluster 3 — Cluster 3 showed almost the opposite pattern. It had a lower median balance than Cluster 2, but a higher median transaction amount,
indicating more active transaction behavior.


CLUSTERING MODEL EVALUATION METRICS

Silhouette Score: 0.484 

Davies-Bouldin Index: 0.844 

Calinski-Harabasz Index: 47803.954

