# Task 3: Retrieving Data from the E-Commerce Database

## Objective

The purpose of this task is to learn how to extract and analyze data from a relational database using different SQL operations such as selecting columns, filtering data with conditions, and sorting results.

## What I Did

### Selected Data from Tables

I began by retrieving data from multiple tables in the e-commerce database:

- Viewed all columns from tables like `Customers`, `Products`, and `Orders` to understand the full dataset.
- Selected only specific columns like customer names, emails, product names, and prices when full data wasn't necessary.
- This helped reduce clutter and focus on the relevant data.

### Filtered Data Using Conditions

To narrow down large datasets and find specific information, I applied different types of filters:

- Checked for customers whose emails end with a specific domain like `@example.com`.
- Found products priced above a certain threshold, such as ₹500.
- Displayed products that belong to a specific category and are also expensive.
- Retrieved order items that fall within a specific price range (e.g., ₹10 to ₹700).
- Fetched payments that are either above ₹100 or used the UPI method.
- Used pattern matching to find emails or product names that follow a specific structure.

These filters helped extract the most relevant data from the tables.

### Sorted Data for Clarity

I organized the output using sorting techniques to better understand trends and rankings:

- Sorted products by available stock in ascending order to find items that may be low in inventory.
- Arranged order items by price in descending order to identify high-value items.
- Displayed payment records in increasing order of amount after filtering out low-value transactions.

Sorting improves readability and helps with business decision-making.

## What I Learned

- How to retrieve complete or partial data from a table.
- How to apply filters to get only the relevant rows.
- How to use multiple conditions together using logical operators.
- How to apply pattern matching to search for specific types of data.
- How to organize and sort result sets for meaningful analysis.

## Screenshots

All output screenshots are available in the `screenshots` folder for visual reference.
