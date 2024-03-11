# Pandas and E-Commerce

## The Challenge
Part 1. Explore the Data

Part 2. Transform the Data

Part 3. Confrim the Work

Part 4. Summarize and Analyze

## Requirements
Explore the Data
1. View the column names.
2. Use the describe function.
3. Correctly identify the category with the most entries.
4. Fro the category with the most entries, correctly identify the subcategory with the most entries.
5. Correctly identify the five clients with the most entries in the data.
6. Store the client ids of those top five clients in a list.
7. Display the total units (the qty column) that the client with the most entries ordered. 

Transform the Data
1. Create a column that calculates the subtotal for each line using the unit_price and the qty.
2. Create a column for the shipping price. Assume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under.
3. Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%.
4. Create a column for the cost of each line using unit cost, qty, and shipping price.
5. Create a column for the profit of each line using line cost and line price.

Confirm the Data
1. Confirm that Order ID 2742071 had a total price of $152,811.89.
2. Confirm that Order ID 2173913 had a total price of $162,388.71.
3. Confirm that Order ID 6128929 had a total price of $923,441.25.

Summarize and Analyze
1. Calculate the total revenue from each of the top five clients in Part 1.
2. Create a sujmary DataFrame showing the totals for the top five clients with the following information: Total Units Purchased, Total Shipping Price, Total Revenue, and Total Profit. Sort by Total Profit.
3. Fromat the data and rename the columns to names suitable for presentation. Currency should be in millions of dollars.
4. Write a brief 2-3 sentance summary of your findings.