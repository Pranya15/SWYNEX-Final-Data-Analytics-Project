# Customer Personality Analysis
### Interactive Data Analytics Dashboard | SWYNEX Internship Project

## 1. Project Overview

Customer Personality Analysis is a data analytics project developed as part of the SWYNEX internship.

The project focuses on analyzing customer demographics, purchasing behaviour, product spending patterns, shopping channels and marketing campaign responses using Microsoft Power BI.

The goal is to transform raw customer data into meaningful business insights through an interactive dashboard.

## 2. Problem Statement

Businesses collect large amounts of customer information, but identifying useful patterns from raw data can be challenging.

This project aims to analyze customer data to understand:
- Who are the customers?
- Which product categories generate the highest spending?
- How does customer income relate to spending?
- Which shopping channels are used most?
- How do customer demographics relate to purchasing behaviour?
- How do customers respond to marketing campaigns?

## 3. Project Objectives

- Clean and prepare the customer dataset.
- Analyze customer demographics and purchasing patterns.
- Calculate important business KPIs.
- Compare spending across product categories.
- Understand shopping-channel preferences.
- Analyze marketing campaign responses.
- Build an interactive Power BI dashboard.

## 4. Dataset Information

**Dataset:** Customer Personality Analysis

**Prepared dataset:** `cleaned_customer_data.csv`

| Attribute | Information |
|---|---|
| Total records | 2,240 |
| Total columns | 30 |
| Customer identifier | ID |
| Demographics | Age, Education, Marital Status, Income |
| Product categories | Wines, Fruits, Meat, Fish, Sweets, Gold |
| Shopping channels | Web, Catalogue, Store |
| Campaign analysis | Response |

## 5. Data Cleaning and Preparation

The following data preparation steps were performed:

1. Checked the dataset structure and data types.
2. Identified 24 missing values in the Income column.
3. Replaced missing Income values using median imputation.
4. Checked for duplicate records and customer IDs.
5. Created an Age calculated column using the reference year 2024.
6. Created an Age Group column to categorize customers.
7. Created a Total Spending column by combining six product spending fields.
8. Used Power Query to unpivot product spending columns into a separate ProductSpending table.
9. Created a one-to-many relationship using the customer ID.

## 6. Tools and Technologies

- **Microsoft Power BI:** Interactive dashboard development.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Calculated columns and measures.
