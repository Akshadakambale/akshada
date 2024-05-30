# Customer Churn Analysis

## Overview
This Power BI project focuses on analyzing customer churn for a telecommunications company. The dashboard provides insights into various factors affecting customer churn, including demographics, service usage, and payment methods. The goal is to help the company understand the reasons behind customer churn and develop strategies to improve customer retention.

## Features
* Key Metrics: Display of total customers, churned customers, and churn rate.
* Demographic Analysis: Insights into churn by gender, age (SeniorCitizen), and tenure.
* Service Usage: Analysis of churn in relation to phone service, internet service, and contract type.
* Payment Method Analysis: Examination of how different payment methods affect churn.
* Financial Insights: Visualization of churn by total charges and monthly charges.

## Visualization
1.Count of CustomerID by Churn: Pie chart showing the proportion of customers who churned vs. those who did not.
<img src="C:\Users\hp\Pictures\customer_churned_analysis\Screenshot 2024-05-29 171804.png">

2.Number of Total Customers by SeniorCitizen and Churn: Bar chart illustrating the churn rate among senior citizens compared to non-senior citizens.


3.Number of Total Customers by PhoneService and Churn: Bar chart showing churn rates among customers with and without phone service.


4.Number of Total Customers by Gender and Churn: Bar chart displaying churn rates for male and female customers.


5.Count of CustomerID by PaymentMethod: Donut chart depicting the distribution of different payment methods among customers.


6.Number of Total Customers by Contract: Bar chart showing churn rates for different contract types (Month-to-month, One year, Two years).


7.Number of Total Customers by TotalCharges: Line chart showing the relationship between total charges and churn.


8.Average Tenure by Churn: Bar chart comparing the average tenure of churned and non-churned customers.


9.Number of Total Customers by InternetService and Churn: Bar chart illustrating churn rates based on the type of internet service (Fiber optic, DSL, No internet service).


10.Churned Customers by MonthlyCharges: Line chart showing the distribution of monthly charges among churned customers.


## Data Sources
Customer Data: Information on customer demographics, service usage, payment methods, and financials.

## Installation
1.Clone the repository to your local machine:
git clone https://github.com/yourusername/your-repo-name.git

2.Open the Power BI Desktop application.

3.Open the .pbix file located in the cloned repository.

4.Ensure that the data sources are properly connected. You may need to update the data source paths or credentials.

## Usage
- Open the Power BI file (.pbix).
- Interact with the dashboard using the filters and slicers to explore different dimensions of the data.
- Use the refresh button in Power BI Desktop to update the data.

## Project Structure
├── data
│   ├── raw                   # Raw data files
│   ├── processed             # Processed data files
├── reports
│   ├── churn_analysis.pbix   # Power BI report file
├── README.md                 # This README file
└── ...

