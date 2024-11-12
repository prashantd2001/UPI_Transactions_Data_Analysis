# UPI_Transactions_Data_Analysis Project with PowerBI

## Project Overview:
This project provides an analysis of UPI transaction data using Power BI. The dataset includes transaction trends, merchant details, payment methods, and user characteristics, offering insights into transaction patterns across different cities, devices, and purposes. By understanding these patterns, stakeholders can better tailor UPI systems for user needs.


## Objective:
To analyze UPI transaction data to:
Identify transaction trends and monthly volume
Understand the distribution of transaction types and purposes
Analyze device types, payment methods, and demographics of users
Provide insights for stakeholders to optimize payment processing.

## Data set used:
- <a href="https://github.com/prashantd2001/UPI_Transactions_Data_Analysis/blob/main/UPI%2BTransactions.xlsx">UPI_Transactions_Dataset</a>

## Dataset:
The dataset contains the following fields:
banknamesent: Bank from which the payment is sent
banknamereceived: Bank receiving the payment
city: The city where the transaction occurred
device type: Device used for the transaction (e.g., Mobile, Tablet)
gender: User's gender
allgroups: Group categorization for users or transactions (e.g., age group)
merchantname: Merchant to whom the payment is made
payment method: Payment method used (e.g., QR code, UPI ID)
purpose: Purpose of the transaction (e.g., bill payment, transfer)
transaction type: Type of transaction (e.g., Payment, Transfer)


## Data Preparation:
1. Data Cleaning: Handling missing values or inconsistencies in transaction fields (e.g., missing bank names, device type).
2. Data Transformation: Parsing date-time fields, standardizing bank names, and categorizing purposes.
3. Data Integration: Integrating data sources as needed for more comprehensive analysis.


## Analysis and Visualizations:
Using Power BI, the following reports and visualizations are created:
Monthly Transaction Trends: Line graph showing monthly transaction volume, which helps identify peak transaction months.
Transaction Breakdown by Type and Purpose: Bar charts illustrating the distribution of transaction types (P2P, P2M) and purposes.
Device Type Analysis: Visualizations showing the breakdown of device types used for transactions.
Bank-to-Bank Transactions: Matrix showing the relationship between banknamesent and banknamereceived.
Merchant Analysis: Visualization of top merchants based on transaction volume and values.
User Demographics: Charts to analyze transactions by user gender, city, and allgroups.
Payment Method Popularity: Bar chart illustrating the most used payment methods.

## Process
1. Verify data for any missing valus and anomalies,and sort out the same.
2. Made sure data is consitent and clean with respect to data type, data format and values used.
3. Created pivot table.
4. Merge all pivot tables into one dashboard and apply slicer to make dynamic. 

## DASHBOARD Interaction:
- <a href="https://github.com/prashantd2001/UPI_Transactions_Data_Analysis/blob/main/Trend%20analysis%20UPI.png">DASHBOARD</a>

## DashBoard
![Trend analysis UPI](https://github.com/user-attachments/assets/2fa4f751-50d1-4458-a9fc-949216b4c991)


## Insights:
Peak Transaction Months: Insights into the months with highest transaction volumes.
Preferred Payment Methods: Identify popular payment methods, useful for optimizing user interfaces.
User Demographics: Breakdown of transactions by gender, city, and group.
Device Type Usage: Helps determine device preferences, which may guide app or service optimization.
Technologies Used
Power BI: For data visualization and report building.
Data Transformation: Power Query for data cleaning and transformation.


## Future Improvements:
Predictive Analysis: Forecasting transaction trends using machine learning models.
Real-Time Analysis: Incorporate real-time transaction data streaming.
Expanded Demographics: Add more demographic fields like age or income to enhance user insights.
Contributing
Contributions are welcome! Please open an issue or submit a pull request if you’d like to contribute to the project.

