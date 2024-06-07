# Customer Behavior Analysis of Loan Property Customers; DIGIFEST by Rakamin 

## Project Overview

This project analyzes customer behavior regarding property type preferences and loan terms based on marital status. The data used is sourced from a CSV file named `loan_customer.csv`, containing information about loan applicants, including gender, marital status, property type, loan term, and other relevant details.

## Steps

1. **Data Loading**: Load the dataset from the CSV file into a Pandas DataFrame.
2. **Data Cleaning**: Ensure the data is clean by handling missing values and removing outliers to prevent data inequality.
3. **Grouping Data**:
   - Group the data by gender and property type to analyze the number of loan applications.
   - Group the data by marital status and loan term to analyze the number of applicants.
4. **Visualization**:
   - Create a bar plot to visualize the distribution of loan applications by property type and gender.
   - Create a bar plot to visualize the distribution of loan applicants by loan term and marital status.

## Results

1. **Property Type Preferences**:
    - Both male and female customers predominantly apply for loans for apartments, indicating a strong preference for this property type.

2. **Borrowing Period by Marital Status**:
    - Both married and unmarried customers consider a 30-year loan term as the ideal borrowing period.
    - Married customers show additional interest in loan terms ranging from 15 to 25 years, possibly due to the financial stability provided by dual incomes.

## Summary

Based on the observations, we conclude that most customers prefer a 30-year loan term, regardless of their marital status. Additionally, married customers are more likely to consider shorter loan terms, possibly due to dual incomes providing financial stability. Both male and female customers show a strong preference for apartments when applying for loans. This analysis provides valuable insights into customer preferences and can help tailor loan products to better meet customer needs.
