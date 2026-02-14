# customer-segmentation

---
**Project Overview**

This project focuses on customer segmentation for an online retail business using the RFM (Recency, Frequency, Monetary) model.

The main objective is to group customers based on their purchasing behavior in order to better understand customer value and support data-driven business decisions such as targeted marketing and customer retention strategies.

The analysis is performed on the Online Retail dataset, which contains transactional data from an e-commerce platform.

**Dataset Description**

The dataset used in this project is OnlineRetail, which contains 541 909 transaction records.
Each row represents a single product transaction made by a customer.

*Dataset columns*:

Column Name   	Description
InvoiceNo	    Unique invoice number for each transaction
StockCode	    Unique product identifier
Description  	Product description
Quantity	    Quantity of products purchased
InvoiceDate 	Date and time of the transaction
UnitPrice   	Price per unit of the product
CustomerID  	Unique customer identifier
Country     	Country where the customer is located


**Project Objectives**

the main goals of this project are :
* Compute RFM metrics (Recency, Frequency, Monetary) for each customer
* Use PySpark to efficiently process and analyze a large-scale dataset (541,909 records), and Perform distributed data transformations and aggregations for scalability and performance.
* Apply K-Means clustering on RFM features to segment customers into distinct groups.
* Track experiments and results using MLflow for reproducibility

**Tools and Technologies Used**

* Python
* Pyspark
* spark Mlib (K-means)
* seaborn & Matplotlib
* MLflow

---


