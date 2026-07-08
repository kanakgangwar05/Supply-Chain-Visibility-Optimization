# Supply Chain Visibility & Optimization - Milestone 1

## Objective

Build a clean and optimized Power BI data model for supply chain analytics by importing, cleaning, transforming, and modeling the dataset using a star schema.

## Dataset Source

The dataset used in this project was obtained from Kaggle.

Source: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis 

## Data Cleaning and Transformation Steps

- Imported CSV into Power BI
- Removed duplicate records
- Handled missing values
- Corrected data types
- Renamed columns where necessary
- Applied Power Query transformations
- Created Fact and Dimension tables
- Built a Star Schema

## Data Model Overview

Fact Table:
- Fact_Orders

Dimension Tables:
- Dim_Date
- Dim_Product
- Dim_Customer
- Dim_Supplier
- Dim_Location

Relationships were created using primary and foreign keys.

## DAX Measures

- Total Sales
- Total Orders
- Total Profit
- Average Delivery Days

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- GitHub
