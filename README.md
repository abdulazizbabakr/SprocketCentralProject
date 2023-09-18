# SprocketCentralProject

# Sprocket Central Data Analysis Project

## Overview

This project focuses on cleaning and exploring the customer data and transaction records of Sprocket Central, a fictional bicycle retailer. The goal of this project is to prepare the data for analysis and provide insights into customer segments, sales patterns, and profitability.

## Project Structure

The project is organized into two main tasks:

### Task 1: Data Cleaning & Normalization

In this task, we performed the following actions:

- Checked the number of columns in each table.
- Ensured data uniqueness by identifying and addressing duplicate records.
- Verified that there were no empty records.
- Checked for NULL values and decided to keep them unless requested by the client.
- Ensured consistency by standardizing values in columns like "gender" and "state."
- Added an "age" column to the CustomerDemographic table and updated it based on date of birth (DOB).
- Deleted an outlier with a customer age of 180.
  
### Task 2: Data Exploration & Model Development

In this task, we conducted exploratory data analysis (EDA) and model development to gain insights into customer profitability. Key analyses include:

- Calculated profit in the Transactions table and created quartile-based profit buckets.
- Added an "age" column to the NewCustomerList table and calculated age based on DOB.
- Analyzed profitability by industry, job title, state, age range, and other factors.
- Identified top-performing customers and matched them with potential new customers.

## Data Sources

The project uses four main data tables:

- CustomerDemographic: Contains customer demographic information.
- CustomerAddress: Contains customer address information.
- Transactions: Contains transaction details, including product sales and profit.
- NewCustomerList: Contains a list of potential new customers.

## Usage

To replicate or modify this analysis:

1. Ensure you have access to the necessary data tables.
2. Execute the SQL queries provided in the project to perform data cleaning, exploration, and analysis.
3. Adapt the queries or analyses as needed for your specific requirements.
4. Use the generated insights to inform marketing strategies, identify potential new customers, and make data-driven decisions.

## Conclusion

This project provides valuable insights into customer profitability, segmentation, and potential new customers for Sprocket Central. The findings can be used to optimize marketing efforts and drive business growth.
