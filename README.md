# Project Sales Insights For Atliq Hardware Company

## Table of Contents
1. [Overview](#overview)
2. [Data Structure & Initial Checks](#data-structure--initial-checks)
3. [Findings and Recommendations](#findings-and-recommendations)
4. [Conclusion](#conclusion)
5. [Acknowledgments](#acknowledgments)

## Overveiw

Atliq Hardware is seeking to better understand the factors behind its declining sales and profitability in order to make informed business decisions. The company aims to gain insights into regional sales performance, customer behavior, and market trends to improve overall profitability and optimize sales strategies.

## Key Objectives:

1. **Analyze Regional Sales Performance**  
   - Identify regions with declining sales and profitability.
   - Compare performance across different regions to pinpoint opportunities for improvement.

2. **Assess Profit Margins**  
   - Identify areas where profitability can be improved and develop strategies for margin optimization.

3. **Optimize Store and Product Performance**  
   - Analyze store performance to understand which stores are contributing most to revenue.
   - Determine underperforming products and identify opportunities to increase sales.


By addressing these objectives, we aim to provide Atliq Hardware with the insights needed to optimize their sales operations and drive business growth.



The **SQL** queries used to **analyze and clean** the data can be found [here](https://github.com/Maaz-Umar-00/Sales-Insights-For-Atliq-hardware/blob/main/03_Sales_insights_in_python-sql.ipynb).

[Click here to Download the  **Power Bi** Dashboard](https://github.com/Maaz-Umar-00/Sales-Insights-For-Atliq-hardware/blob/main/02_Atliq_hardware_sales_project.pbix)


## Data Structure & Initial Checks
The dataset used for this analysis is sourced from [https://codebasics.io/resources/sales-insights-data-analysis-project]) and it includes **Five tables**.

![Data Model Or Data Structure](./04_Chart_pics/Data_Structure.png
)

## Findings and Recommendations
1.# Atliq Hardware Revenue Analysis

- **Atliq Hardware's revenue peaked at $43 million in 2018, but declined by approximately 65% to $15 million by 2020.**
- **Atliq Hardware** could consider implementing a subscription model for regular customers, allowing them to receive monthly supplies at a discounted rate, thereby ensuring steady revenue. 
![Revenue Trends by Date](./04_Chart_pics/revenue_by_date.png)



![Utility Spending Patterns](./03_Chart_pics/Percentage_of_spending_income_Based_on_different_items.png
)
2. **City-Specific Spending Patterns**:
   - The analysis indicates that people spend the most in **Mumbai** and the least in **Hyderabad**, highlighting the need for tailored marketing strategies to maximize engagement in both markets.
   - This suggests that Mitron Bank should consider developing city-specific promotions and offers that resonate with the local consumer base.

![City Specific Spending Patterns](./03_Chart_pics/Total_spending_per_city.png)

 
3. **Payment Card Usage Among IT Employees**:
   - The analysis shows that **IT employees** use the most variety of payment cards, presenting an opportunity for Mitron Bank to offer specialized cards that cater to their diverse spending habits.
   - This could enhance customer loyalty and encourage greater usage of the bank’s offerings by providing tailored features and rewards that meet the specific needs of this demographic.

![IT Employees Payment Card Usage](./03_Chart_pics/Payment_card_usage_by_work_type.png)
![Work_type](./03_Chart_pics/work_type_colours.png)

     
To access full **Tableau dashboard,** please click [here](https://public.tableau.com/app/profile/maaz.umar/viz/MitronBankAnalysis_17266593076560/05_credit_card_dashboard)\
To access **Sql queries** click [here](https://github.com/Maaz-Umar-00/Mitron-Bank-Analysis-Project/blob/main/01_Payment_card_Analysis_in_Sql.ipynb)

## Conclusion
This analysis provides valuable insights into **customer spending patterns** that can guide **Mitron Bank in introducing new payment card products.** By understanding the diverse needs and preferences of different customer segments, the bank can create tailored solutions that enhance customer engagement and loyalty.

## Acknowledgments
* [code_basics](https://codebasics.io/challenge/codebasics-resume-project-challenge/11) for providing the dataset.\
* **Tableau** and **sql** for visualization and insights.


