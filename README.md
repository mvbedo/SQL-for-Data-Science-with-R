# SQL-for-Data-Science-with-R

## Assignment Scenario

I’ve been hired by a US Venture Capital firm as a data analyst. My first task involves analyzing crop production in Canada to assist the company in evaluating foreign grain markets for their microbrewery and microdistillery investments. The goal is to provide a high-level analysis of crop performance in Canada, focusing on supply and price volatility, and understanding how these relate to the Canadian and US dollars.

## Introduction

In this R notebook, I will:

1. Understand four datasets.
2. Load these datasets into separate tables in a database.
3. Execute SQL queries to address assignment questions.

I will use prior work from practice labs to prepare the database tables for SQL queries.

## Understanding the Datasets

For this assignment, I'll work with three key datasets:

1. **Canadian Principal Crops Data**
   - **Description**: Contains agricultural production measures for principal crops in Canada, including provincial and territorial breakdowns, from 1908 to 2020.
   - **Details**: [StatsCan Data Portal](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210035901)

2. **Farm Product Prices**
   - **Description**: Provides monthly average farm product prices for Canadian crops and livestock by province and territory, from 1980 to 2020.
   - **Details**: [StatsCan Data Portal](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210007701)

3. **Bank of Canada Daily Average Exchange Rates**
   - **Description**: Includes daily average exchange rates for multiple foreign currencies, including USD-CAD, for the past four years. The data is published daily and I will use the monthly averaged version for this analysis.
   - **Details**: [Bank of Canada Data Portal](https://www.bankofcanada.ca/rates/exchange/daily-exchange-rates/)

I will use preprocessed snapshots of these datasets to streamline the analysis process.
