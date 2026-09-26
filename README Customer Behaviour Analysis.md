# Customer Behaviour Analysis

An exploratory data analysis of e-commerce/retail customer purchase data, using T-SQL and Python, to understand spending patterns, purchase frequency, and subscription likelihood.

## Overview

This project analyzes customer-level purchase data to answer three main questions: how much and how often customers spend, what patterns distinguish higher- vs. lower-value customers, and which customers are more likely to subscribe to the business’s services. Data is first cleaned in Python (Pandas), then the resulting dataframe is transferred into SQL Server Management Studio (SSMS), where T-SQL queries are used for further analysis.

## Contents

|File                                     |Description                                                                                                    |
|-----------------------------------------|---------------------------------------------------------------------------------------------------------------|
|`Customer Behaviour Analysis.ipynb`      |Python/Jupyter notebook that cleans the raw purchase data and transfers the resulting dataframe into SQL Server|
|`Customer Behaviour Analysis (T-SQL).sql`|T-SQL queries analyzing customer spending patterns, purchase frequency, and subscription likelihood            |

## Research Questions

1. What do customer spending patterns look like, and how do they vary across the customer base?
1. How frequently do customers purchase, and what does that suggest about engagement?
1. Which customer behaviours are associated with a higher likelihood of subscribing to the business’s services?

## Skills Demonstrated

- Data cleaning in Python (Pandas)
- Transferring a cleaned dataframe from Python into SQL Server for further analysis
- T-SQL querying, aggregation, and grouping of customer transaction data
- Translating a business question (subscription likelihood) into an analytical approach

## Tools Used

- **Python (Pandas, Jupyter Notebook)** — data cleaning and dataframe-to-SQL transfer
- **SQL Server (T-SQL / SSMS)** — querying and aggregating customer purchase data

## How to Use

1. Open `Customer Behaviour Analysis.ipynb` in Jupyter and run it to clean the raw purchase data and load the cleaned dataframe into SQL Server.
1. Run `Customer Behaviour Analysis (T-SQL).sql` in SSMS to reproduce the analysis of spending, frequency, and subscription patterns.

## Author

Sam