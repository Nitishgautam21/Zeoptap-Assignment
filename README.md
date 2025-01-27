# Data Science Assignment: eCommerce Transactions Dataset

## Overview
- **Objective:** To perform exploratory data analysis (EDA), build predictive models, and derive actionable insights on given datasets.
- **Provided Datasets:** Customers.csv, Products.csv and Transactions.csv

## Repository Structure
The repository consists of a single main branch and the following files and folders:
<pre>
├── Nitish_Gautam_Clustering.ipynb          # Clustering Jupyter Notebook |
├── Nitish_Gautam_Clustering.pdf            # Clustering Report
├── Nitish_Gautam_EDA.ipynb                 # EDA Jupyter Notebook
├── Nitish_Gautam_EDA.pdf                   # Business insights Report
├── Nitish_Gautam_Lookalike.csv             # Lookalike csv file
├── Nitish_Gautam_Lookalike.ipynb           # Lookalike Jupyter Notebook
└── README.md                               # Project documentation
</pre>

## Files Description
- **Nitish_Gautam_Clustering.ipynb:** This Jupyter Notebook focuses on customer segmentation using the K-means clustering algorithm.
  
- **Nitish_Gautam_Clustering.pdf:** This PDF report presents a detailed analysis of the customer segmentation process carried out in the Nitish_Gautam_Clustering.ipynb notebook. It includes an overview of the clustering methodology, the K-means algorithm, and the reasoning behind the chosen features for segmentation.
  
- **Nitish_Gautam_EDA.ipynb:** This Jupyter Notebook contains the Exploratory Data Analysis (EDA) for the provided dataset. It involves data cleaning, transformation, and visualization to understand key trends, relationships, and insights within the data.
  
- **Nitish_Gautam_EDA.pdf:** This report presents key business insights from the Exploratory Data Analysis (EDA) of the dataset:
  -Customer Segmentation: Identifying distinct customer groups based on RFM (Recency, Frequency, Monetory) Values.
  - Regional Preferences: Analyzing product and category preferences by region.
  - Transaction Patterns: Observing trends in transaction and sales throughout year.
  - Product Popularity & Sales Trends: Tracking top-selling products and sales trends.
  - Customer Lifetime Value (CLV): Estimating the long-term value of customers.

- **Nitish_Gautam_Lookalike.csv:** This file contains the top 3 lookalike customers along with their similarity scores for the first 20 customers. Each record maps the CustomerID to a list of their top 3 lookalikes and the corresponding similarity scores.

- **Nitish_Gautam_Lookalike.ipynb:** This Jupyter Notebook contains the code used to generate the Lookalike.csv file. It calculates the similarity scores between customers using cosine similarity and identifies the top 3 lookalike customers for the first 20 customers.
