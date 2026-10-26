
Customer Retention and Churn Analysis

1. Project Overview

This project analyzes customer subscription data to understand why customers leave a service and identify opportunities to improve customer retention.

The analysis focuses on churn rates, customer tenure, contract types, monthly charges, and customer segments. The goal is to provide useful insights and recommendations for a subscription-based business.

2. Objectives

- Clean and organize the customer dataset.
- Calculate the overall customer churn rate.
- Identify customer segments with higher churn.
- Analyze customer tenure and retention patterns.
- Study the relationship between contract type and churn.
- Examine monthly charges and service subscriptions.
- Recommend strategies to improve customer retention.

3. Dataset Description

The project uses the Telco Customer Churn dataset.

The dataset includes customer information such as:

- Customer ID
- Gender and senior-citizen status
- Partner and dependent status
- Tenure in months
- Phone and internet services
- Contract type
- Payment method
- Monthly charges
- Total charges
- Churn status

The "Churn" column indicates whether a customer has left the service.

4. Data Cleaning and Preparation

The following checks will be performed:

1. Check the dataset dimensions and column names.
2. Identify missing or blank values.
3. Check for duplicate records.
4. Convert numeric columns to appropriate data types.
5. Verify that the churn column contains valid categories.
6. Prepare the data for analysis.

The "TotalCharges" column should be checked carefully because some records may contain blank values.

5. Key Performance Indicators

Customer Churn Rate

Churn rate measures the percentage of customers who left the service.

Formula:

Churn Rate = (Number of Churned Customers / Total Customers) × 100

Customer Retention Rate

Retention rate measures the percentage of customers who remained with the service during the measured period.

For a simple dataset-based comparison:

Retention Rate = (Number of Customers Who Stayed / Total Customers) × 100

Average Customer Tenure

Average tenure measures how long customers have been with the company.

Average Tenure = Sum of Customer Tenure / Total Number of Customers

6. Exploratory Data Analysis

The following comparisons will be performed:

Churn by Contract Type

Compare churn among month-to-month, one-year, and two-year contract customers.

Churn by Tenure

Examine whether customers with shorter or longer tenure are more likely to churn.

Churn by Monthly Charges

Compare monthly charges for customers who churned and customers who stayed.

Churn by Internet Service

Study churn patterns across different internet service types.

Churn by Payment Method

Compare churn across different payment methods.

Customer Retention Patterns

Identify customer groups that may need additional support or retention offers.

7. Expected Visualizations

The project will include:

- Churned versus retained customer chart
- Churn rate by contract type
- Churn by tenure group
- Churn by internet service
- Churn by payment method
- Monthly charges comparison

8. Business Recommendations

The following recommendations will be evaluated against the actual analysis results:

1. Improve onboarding: Provide additional guidance and support to new customers.
2. Encourage longer-term contracts: Offer suitable benefits to customers who choose longer subscriptions.
3. Monitor at-risk customers: Identify customer segments with high churn and investigate their needs.
4. Review pricing: Examine whether higher monthly charges are associated with churn.
5. Improve customer support: Make it easier for customers to resolve issues quickly.
6. Personalize retention offers: Provide relevant offers based on customer needs and subscription history.

These recommendations should be refined after the data analysis confirms which factors are most strongly associated with churn.

9. Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook or Google Colab
- GitHub

10. Conclusion

Customer churn analysis helps businesses understand customer behavior and identify opportunities to improve retention.

This project will use data cleaning, exploratory analysis, statistical summaries, and visualizations to identify churn patterns and develop evidence-based business recommendations.

Project Status: Analysis in progress.

11. Deliverables

- Customer churn dataset
- Data cleaning and analysis
- Data visualizations
- Key findings and recommendations
- Final project report
