# Sales and Product Management Dashboard
# Problem Statement
Our sales reporting system relies on static reports that require more flexibility and depth for practical analysis. We must transition from static reports to dynamic visual dashboards to enhance our sales monitoring and decision-making process. 
The primary challenges we face are:

* __Lack of Detailed Product and Client Insights__: We cannot currently track the sales of individual products and understand the clients associated with each sale. This hampers our ability to tailor our sales strategies effectively.
* __Inability to Assess Performance Trends__: We need a comprehensive system for evaluating the performance trends of our sales over time. This makes it difficult to make informed decisions and adapt to changing market dynamics.
* __Budgetary Comparison__: Our budget data for the fiscal year 2022 needs to be more effectively integrated into our sales reporting, limiting our ability to compare actual sales performance against budgeted targets.

* __Need for Filter Functionality__: Given the diverse range of products and clients managed by each salesperson, we require the capability to apply filters to analyze specific segments of our sales data.

# Business Understanding

## Business Demand Overview: 
-  __Reporter__: Shenique N. – Sales Manager
-  __Value of Change__: Visual dashboards and improved Sales reporting for Salesforce.
-  __Necessary Systems__: PowerBI, CRM System
-  __Other Relevant Information__: Budgets have been delivered in Excel for 2022

## User Stories:
| No. | As a          | I want                                | So that                                 | Acceptance Criteria                                  |
| --- | ------------- | ------------------------------------ | --------------------------------------- | ----------------------------------------------------- |  
| 1   | Sales Manager | to access a PowerBI dashboard        | effectively track which customers and products perform best each month/quarter/year | A PowerBI dashboard updated once daily.   |
| 2   | Sales Rep     | A detailed PowerBI dashboard         | proactively engages with our most frequent customers and identifies potential future sales opportunities | A PowerBI dashboard that provides the functionality to filter data by each customer. |
| 3   | Sales Rep     | a detailed overview of sales per product | efficiently monitor and manage the products that are selling the best | A PowerBI dashboard that provides the functionality to filter data by each product. |
| 4   | Sales Manager | comprehensive PowerBI dashboard to oversee our sales performance over time, enabling a comparison against our budget | can effectively evaluate our sales performance | A PowerBI dashboard that includes graphs and Key Performance Indicators (KPIs) to facilitate a comparison with the budget. |

# Data Understanding
**Data Source:** [AdventureWorks 2022 Sample Database](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms) The project utilizes the AdventureWorks 2022 sample database, a comprehensive dataset provided by Microsoft, designed for learning and practicing SQL and database management. 

This database contains information about a fictional bicycle manufacturer, Adventure Works Cycles, and encompasses various aspects of its operations, including sales, products, customers, and more. 
#### Key Tables and Data Categories 
##### Fact Tables
1. **Internet Sales Data:** The database contains sales-related information, including orders, order details, and sales territories.
1. **Budget:** Data about budgets and financial performance.

##### Dimension Tables
1. **Product Data:** Information about products, categories, and descriptions.
1. **Customer Data:** Customer details, including names, addresses, and contact information.
1. **Calendar Data:** Information about the year, quarter, month and day descriptions.
  


The data in AdventureWorks 2022 is designed to support a wide range of scenarios and use cases for database and SQL practice. This README file covers the data's use in improving sales reporting and creating dynamic visual dashboards. Please ensure the AdventureWorks 2022 database is installed and accessible for this project.

# Data Preparation
To clean and transform this data, I used Microsoft Power BI, Power Query