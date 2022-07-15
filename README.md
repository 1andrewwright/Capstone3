# Customer Segmentation
![cover_photo](readme/customer_market.jpg)

**Background**

In the world of busines, customers have all kinds of different needs and backgrounds. Effective marketing can tailor to the differences in needs, background and behaviors. The following project takes a dataset of online retail data and, using data munging, data anlysis and machine learning, results in a customer segmentation and cohort anlysis to be used for more efficient marketing and sales.

**Problem Statement**

Prepare a report and presentation on insights and customer segmentation that can be acted upon by a marketing to increase overall product sales by 10% by next quarter.

**Data**

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Dataset Features:
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.
  
**Solution Approach**
  - Understand the given data thoroughly. What are the features and what are the values.
  - Data Wrangling. Resolve missing values. Check for categorical variables inconsistencies. Check for numerical outliers. 
  - Exploratory data analysis. Visualize the data in different forms to get insights into. Find out relations between target and each data column.
  - Preproccessing. Normalize features included distribution and scaling.
  - Calculate Cohort Analysis and RFM for dataset.
  - Fit different unsupervised algorithms like clustering and Kmeans. Compare models and use snake plots and heatmaps.
  - Create a segmentation using Tableau.
  - Make a report mentioning the details about the chosen model and how to apply it to predict revenue from customers.
    
**Deliverables**
  - Developed Code in Python Notebooks
  - Final Report with findings
  - Slide deck
  - Tableau Dashboard






