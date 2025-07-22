# Excel-project
Myntra
Myntra-Apparel-Dataset-Analysis-Project
Project Overview

This project focuses on analyzing Myntra's apparel dataset to extract valuable insights into pricing, discounts, ratings, and available sizes. The dataset was cleaned, prepared, and analyzed using various Excel features and formulas to answer key business questions.

Dataset Link: https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view
Problem Statement:

You are working at Myntra, a leading online fashion retailer. The management has asked you to analyze a dataset of various apparel items to gain insights into pricing, discounts, ratings, and available sizes.
Project Questions

    A. Data Cleaning and Preparation

    Check for duplicate values in your dataset and remove them.
    Standardize the "DiscountOffer" column to a single format, ensuring all values are uniform.
    Identify rows where both "DiscountPrice" and "DiscountOffer" are null and fill the "DiscountPrice" with the average discount price of the respective category.
    Replace all null values in the "SizeOption" column with the text "Not Available."

    B. Data Analysis

    Calculate the overall average original price for products with ratings greater than 4.
    Count the number of products with a discount offer greater than 50% OFF.
    Count the number of products available in size "M."
    Create a new column to label the products as "High Discount" if the discount offer is greater than 50% OFF, otherwise label them as "Low Discount."

    C. Data Retrieval and Lookup

    Use VLOOKUP/XLOOKUP to find the product brand, price, and rating of the product with Product_id "11226634".
    Find the "DiscountPrice" for the product with the Product ID "6744434" using the INDEX and MATCH functions.
    Utilize nested xlookup to find any column’s detail of a product with it’s product id.

Data Cleaning and Preparation

    Duplicate Removal: Identified and removed duplicate rows to ensure data accuracy.
    Discount Standardization: Uniform formatting applied to the "DiscountOffer" column for consistency.
    Null Value Imputation: Filled missing "DiscountPrice" values with the average discount price of the respective category and replaced null "SizeOption" entries with "Not Available."

Data Analysis

    Average Price Calculation: Calculated the overall average original price for products with ratings above 4 using AVERAGEIF.
    Discount Count: Counted products with more than 50% discount using COUNTIF.
    Size Availability: Counted the number of products available in size "M" with COUNTIF.
    High vs Low Discount Labeling: Added a "High Discount" label for products with discounts over 50% using the IF function.

Data Retrieval and Lookup

    Product Lookup: Used XLOOKUP to retrieve product details (brand, price, rating) for Product_id "11226634".
    DiscountPrice Lookup: Retrieved the "DiscountPrice" for Product ID "6744434" with INDEX and MATCH.
    Nested Lookups: Implemented nested XLOOKUP for advanced column detail retrieval based on product ID.

Key Excel Features Used

    Data Cleaning: Remove Duplicates, IFERROR.
    Analysis Functions: AVERAGEIF, COUNTIF, IF.
    Lookups: VLOOKUP, XLOOKUP, INDEX & MATCH.
    Conditional Formatting: Applied for quick visual insights.

Conclusion

This project effectively utilized Excel’s powerful features to gain actionable insights from the Myntra dataset, helping in strategic decision-making for pricing, discount strategies, and product availability.
