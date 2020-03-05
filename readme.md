## Problem Statement:

Online retail is a transnational data set which contains all the transactions occurring 
between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.
The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

The company want to find some desired customer for upcoming occassions.



Working Procedure:

There are many tecniques to solve different business case study.I used RFM method.RFM means Recency , Frequency , Monetory.


### Recency

How recently u visited the store and purchased


### Frequency

Frequency is how much purchased a customer in one year.Example if it 50,then the customer purchased 50 product last year.


### Monetory

How much customer spend on purchasing..It is described in dollar.



## Outlier Detection:

Kmeans is highly impected by outlier..so there is also a tecnique for outlier checking
i check this using Inter-Quantile tecnique.
If the value is (q1(firest-interquantile & q3(third-interquantile)) between them then it is not a outlier.



## Hopkins Statistics:
This method is for finding best cluster from dataset.

- If the value is between {0.01, ...,0.3}, the data is regularly spaced.

- If the value is around 0.5, it is random.

- If the value is between {0.7, ..., 0.99}, it has a high tendency to cluster.



## Silhouette Analysis

* The value of the silhouette score range lies between -1 to 1. 

* A score closer to 1 indicates that the data point is very similar to other data points in the cluster, 

* A score closer to -1 indicates that the data point is not similar to the data points in its cluster.



### Finally see some graph it can be determined which are the desired customer for this company.
