# ECommerce-Customer-Segmentation
# Customer Segmentation using RFM Analysis

This repository hosts the project on customer segmentation using the RFM (Recency, Frequency, Monetary) analysis technique. Conducted as part of the e-commerce analytics exploration, this project leverages the "Online Retail" dataset from the UCI Machine Learning Repository, encompassing transactions from an online retail non-store firm.

## Project Overview

RFM analysis is employed to segment customers based on their transaction history, focusing on how recently and frequently they have purchased, and the monetary value of their purchases. This segmentation helps in crafting targeted marketing strategies and enhancing customer engagement.

### Objectives
- Perform a thorough RFM analysis to segment customers into distinct groups based on transaction patterns.
- Utilize these segments to derive insights for effective marketing and enhanced customer relationship management.

### Dataset Overview
The dataset captures transactions between December 2010 and 2011, providing insights into consumer interactions during this period. Key data fields include Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.

### Methodology
- **Data Preprocessing**: Handling missing values, converting data types, and ensuring data integrity.
- **RFM Calculation**: Computing RFM metrics for each customer to aid in segmentation.
- **Customer Segmentation**: Applying clustering techniques like K-Means and Agglomerative Hierarchical Clustering to segment customers based on RFM scores.

### Results and Discussion
Segment profiles were developed, providing a granular view of customer behavior. Key findings include:
- Identification of high-value customers who are recent and frequent buyers.
- Insights into customer loyalty and purchasing patterns, informing targeted engagement strategies.

## Files in the Repository
- `FDA Project 2 Code.ipynb`: Jupyter notebook containing all the analysis code.
- `FDA Project 2.pdf`: Detailed project report with methodology, analysis, and results.

## Visualizations
-performing customer segmentation using two different clustering algorithms
![image](https://github.com/sreeyagalla/ECommerce-Customer-Segmentation/assets/163912617/5f197f4c-954c-4c74-bb24-f5e94f8b46ed)

-histograms showing the distribution of Recency, Frequency, and Monetary values in the entire dataset
![image](https://github.com/sreeyagalla/ECommerce-Customer-Segmentation/assets/163912617/20abf4a2-798d-4ce2-9553-90d9cd7119b9)

-A heatmap summarizing mean RFM values for each cluster
![image](https://github.com/sreeyagalla/ECommerce-Customer-Segmentation/assets/163912617/845ae0b9-739e-4b5f-8908-5a8bb652802e)


## Conclusions
This project underscores the utility of RFM analysis in understanding customer behavior and enhancing strategic decision-making in e-commerce. The segmentation enables tailored marketing approaches, optimizing resource allocation and customer retention strategies.

## How to Use
1. Clone this repository to your local machine.
2. Open the `FDA Project 2 Code.ipynb` in a Jupyter environment to view and run the analysis.
3. Review the `FDA Project 2.pdf` for a comprehensive report on the project's scope, methodology, and findings.


