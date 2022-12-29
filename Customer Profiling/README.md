# Overview
* Engineered several features for a cleaner and more informative analysis
* Processed the data with Principal Component Analysis (PCA) to reduce the dimensionality of the data down to 3 features.
* Used agglomerative clustering and K-Means clustering to identify groups of customers that exhibited similar characteristics.
* Profiled 4 groups of customers that varied on income, expenses, marriage status, chuldren, and more.

## Code and Resources Used
**Python Version:** 3.9 <br>
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

## Results
**Agglomerative Clustering**
* Silhouette score: 0.32

**K-Means Clustering**
* Silhouette score: 0.35

**Cluster Characteristics** <br> <br>
Cluster 0
* Likely has multiple children.
* Low to average income.
* Low to average spending.
* Tends to be older in age.

Cluster 1
* Low income.
* Low spending.
* Tend to be younger in age.

Cluster 2
* Average to high income
* Average to high spending.
* Like to have children.
* Tends to be older in age.

Cluster 3
* High income.
* High spending.
* Unlikely to have children.
* Age can vary.


## Conclusions
* K-Means clusters seemed to be a bit more similar to its own cluster and more different than other clusters (silhouette score), but both algorithms came up with similar clusters.
* Overall, there was low participation is promotional campaigns, but, as expected, the groups of customers with more income and higher expenses tended to participate in more promotional campaigns.
* When it came to deals released by the company, the groups with moderate income and expenses participated at high rates whereas the higher income/expense group did not.
