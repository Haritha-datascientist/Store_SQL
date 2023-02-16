# Store_SQL
Problem Statemnt:
As a database administrator, you have been tasked with analyzing customer data to gain insights into their behavior and preferences. Your goal is to answer a range of questions about sales and profits across different states, marketing spend, and other factors such as cost of goods sold (COGS) and budget profit.

Your analysis will help you identify which items are selling the most and which states are generating the highest sales and profits. You also need to generate basic datasets for your team to use so they can easily access and analyze the data without needing to use SQL.

Due to privacy concerns, you have been provided with a sample of the customer data. However, you believe this is sufficient to write fully functional SQL queries and generate meaningful insights that will help inform business decisions.

Dataset :
The 3 key datasets for this case study:
* FactTable
The FactTable has 13 columns mentioned below and 4200 rows.
Profit, Margin, Sales, COGS, Total Expenses, Marketing, Inventory, Budget, Profit, Budget
COGS, Budget Margin, Budget Sales, Area Code, and ProductID
Note - COGS stands for Cost of Goods Sold
* ProductTable
The ProductTable has four columns named Product Type, Product, ProductId, and Type. It has
13 rows, which can be broken down into further details to retrieve the information mentioned in
the FactTable.
* LocationTable
Finally, the LocationTable has 156 rows and follows a similar approach to ProductTable and has
four columns named Area Code, State, Market, and Market Size.
