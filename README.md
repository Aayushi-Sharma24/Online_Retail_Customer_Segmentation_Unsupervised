# Online_Retail_Customer_Segmentation_Unsupervised

## Problem Statement
In this project, we have to identify major customer segments on a transnational dataset, for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Dataset Information
* No of observations – 541909
*	No of features  - 8

## Features information:
* **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
*	**StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
*	**Description**: Product (item) name. Nominal.
*	**Quantity**: The quantities of each product (item) per transaction. Numeric.
*	**InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
*	**UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
*	**CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
*	**Country**: Country name. Nominal, the name of the country where each customer resides. 

## Project Workflow
* EDA
* Handling Null value
* Outlier treatment
* Feature Scaling 
* RFM analysis
* Optimal number of cluster selection using:
  * Silhouette Score 
  * Elbow Method
* Clustering 
  * K means Clustering
  * Hierarchial Clustering
  * DBSCAN

## Conclusion
K means Clustering with silhouette gives highest score with number of clusters = 2

The customer segments thus deduced can be very useful in targeted marketing, scouting for new customers and ultimately revenue growth. After knowing the types of customers, it depends upon the retailer policy whether to chase the high value customers and offer them better service and discounts or try and encourage low/ medium value customers to shop more frequently or of higher monetary values.
