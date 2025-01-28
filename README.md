Data Science Assignment: eCommerce Transactions Dataset

Overview

This project involves analyzing eCommerce transaction data from three datasets (Customers.csv, Products.csv, and Transactions.csv). The assignment includes tasks on Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation using clustering techniques.

Repository Structure

|-- FirstName_LastName_EDA.ipynb
|-- FirstName_LastName_EDA.pdf
|-- FirstName_LastName_Lookalike.ipynb
|-- FirstName_LastName_Lookalike.csv
|-- FirstName_LastName_Clustering.ipynb
|-- FirstName_LastName_Clustering.pdf
|-- README.md

Requirements

Python 3.x

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Dataset Description

Customers.csv

CustomerID: Unique identifier for each customer

CustomerName: Name of the customer

Region: Continent where the customer resides

SignupDate: Date when the customer signed up

Products.csv

ProductID: Unique identifier for each product

ProductName: Name of the product

Category: Product category

Price: Product price in USD

Transactions.csv

TransactionID: Unique identifier for each transaction

CustomerID: ID of the customer who made the transaction

ProductID: ID of the product sold

TransactionDate: Date of the transaction

Quantity: Quantity of the product purchased

TotalValue: Total value of the transaction

Price: Price of the product sold

Tasks

Task 1: Exploratory Data Analysis (EDA) and Business Insights

Perform EDA on the dataset.

Visualize key insights using plots.

Derive at least 5 business insights.

Deliverables:

FirstName_LastName_EDA.ipynb: Jupyter Notebook containing EDA code.

FirstName_LastName_EDA.pdf: PDF report summarizing business insights.

Task 2: Lookalike Model

Build a Lookalike Model that recommends 3 similar customers for each of the first 20 customers.

Use both customer and product information.

Assign a similarity score to each recommended customer.

Deliverables:

FirstName_LastName_Lookalike.ipynb: Jupyter Notebook containing the Lookalike Model.

FirstName_LastName_Lookalike.csv: CSV file with the lookalike recommendations in the format:

cust_id, List<cust_id, score>
C0001, [(C0010, 0.85), (C0025, 0.82), (C0032, 0.80)]

Task 3: Customer Segmentation / Clustering

Perform customer segmentation using clustering techniques.

Use both profile information and transaction information.

Optimize the number of clusters between 2 and 10.

Calculate clustering metrics, including the DB Index.

Visualize clusters.

Deliverables:

FirstName_LastName_Clustering.ipynb: Jupyter Notebook containing clustering code.

FirstName_LastName_Clustering.pdf: PDF report summarizing clustering results.

Evaluation Criteria

Task

Weightage

Exploratory Data Analysis

25%

Business Insights

15%

Lookalike Model

30%

Customer Segmentation

30%

Instructions

Ensure all deliverables are named according to the required format.

Push all files to a public GitHub repository.

Include this README.md file in the repository.
