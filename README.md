# Financial-analysis
You can find more about me here: [James Oladejo](https://linkedin.com/in/james-oladejo-2000/)

## Introduction
The main goal of this project was to derive insights into the financial performance of three business lines for a particular fitness company. 
- Sports Equipment
- Sportswear
- Nutrition and Food Supplement

### The dataset
The dataset was provided by Onyx Data for the August 2024 #DataDNA challenge. 
It contains a table with the following attributes: 
- Year: Year of revenue/expense
- Month - name:	Month of revenue/expense
- Month - sequence:	Month of revenue/expense, expressed as number
- Date:	Date of revenue/expense, expressed as the last day of the month
- Business Line:	Business line generating revenue / expense (Sports Inventory, Sportswear, and Nutrition & Food Supplements)
- Amount, $:	Revenue or expense amount in USD
- Expense subgroup:	Additional subgroups categorizing expenses associated to OPEX and COGS
- Income / Expense Group:	Subcategory of revenue / expense. Revenue subcategories are Sales, Consulting and Professional Services and Other income). Expense subcategories are OPEX, COGS and Interests and Tax
- Income or expense:	Column indicating if associated amount is revenue or expense

### Data Cleaning, Transformation and Modelling
The data quality was okay for the king of analysis I intend to carry out, however, I added additional tables to the dataset to make the model perform well, and the DAX measures run effectively. These are the additional tables that were added:
- I splited the revenue-expense into two:
  - The revenue table
  - The expense table
- I added a Date table

I then proceeded to write DAX measures to generate insights from my data. 

## Insights 
These are the insights gotten from my analysis
- A total of $17.56 million was generated in revenue across the three business lines
- $13.25 million was incured in expenses across the three business lines
- The Cost of Goods Sold(COGS) was $6.71 million
- The Business recorded a Net profit of $4.31. This means that the business profitability as indicate by the Profit margin is 24.57%
- The performance of the business lines were also explored:
    - Sports equipment (Revenue: $8.91M, Expenses: $6.62M, Net Profit: $2.29M)
    - Sportswear (Revenue: $6.81M, Expenses: $4.07M, Net Profit: $2.74M)
    - Nutrition and Food Supplements (Revenue: $1.84M, Expenses: $2.56M, Net Profit: -$712.88K)
    The Nutrition and Food Supplements appears to be the less profitable, because it incured more expenses than the total revenue it generated.
- The main revenue driver appears to be the Sports equipment business line.


## Recommendations
1. The first step is to identify the root cause of losses in the Nutrition and Food Supplements business line.
   - From my Root cause analysis, Payroll and Labor cost were the greatest expense activity for the business line
   - Some strategies can be implemented to reduce expenses either by converting labor manpower to permanent staffs. Permanent staffs earn 50% less than Labor staffs.
   - New products should be introduced as well. Just to diversify the revenue stream

2. The Sports equipment Business line was seen to be successful. One action I would recomment would be to leverage on this success by: 
  - Invest in marketing and sales effort to expand the customer base
  - New products line should be introduced to further drive the revenue
  - One area to cut cost is the cost of Labor.

## Conclusion
In conclusion, the financial analysis reveals a mixed performance across the three business lines. While the Sports Equipment and Sportswear divisions demonstrated profitability, the Nutrition and Food Supplements segment incurred significant losses. To rectify this, a comprehensive review of the underperforming line is crucial to identify cost-saving measures and revenue-generating opportunities. A strategic focus on the successful Sports Equipment line, coupled with diversification efforts, can bolster overall business performance.

Thank you! 
James Oladejo. 


  
