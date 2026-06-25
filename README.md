
# DataCo-Global-Revenue-Profit-Customer-Analytics
Data analytics project analyzing DataCo's global supply chain operations using Excel, SQL Server, and Power BI to uncover revenue trends, profitability drivers, customer behavior, regional performance, and business insights.

## Dataset Source

Original Dataset:
DataCo Smart Supply Chain Dataset (Kaggle)

https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Cleaned Dataset

The original DataCo dataset was cleaned and transformed in Microsoft Excel before analysis.

### Data Cleaning Activities

- Removed unnecessary columns
- Standardized date formats
- Created Profit Margin (%) column
- Created Margin Category (High, Mid, Low)
- Checked for missing values
- Validated duplicate records

### Cleaned Dataset Access

Due to GitHub file size limitations, the cleaned dataset is available through Google Drive:
Download Cleaned Dataset:
https://drive.google.com/your-link-here


## SQL Analysis

### Query 1: Revenue and Average Benefit Analysis

This query calculates total revenue and average benefit by customer segment and department.

### Insight

The analysis revealed that Consumer customers generated the highest revenue overall. Among all departments, the Fan Shop department contributed the largest share of revenue, indicating strong customer demand and sales performance within this product category.

### Result
<img width="1365" height="726" alt="SQL Query 1 Revenue Analysis" src="https://github.com/user-attachments/assets/1216747b-0282-414e-bc19-384a3d3eb15c" />

### Query 2: Repeat Customer Analysis

This query identifies customers with three or more orders and evaluates customer purchasing behavior.

### Insight

The analysis revealed that repeat customers contributed significantly to overall revenue due to their higher purchase frequency. This suggests that customer retention plays an important role in driving sales performance and long-term business growth

### Result
<img width="1358" height="727" alt="SQL Query 2 Repeat Customers" src="https://github.com/user-attachments/assets/7e69e31e-ada5-4cc6-ac95-8b33fdfc2d7d" />


### Query 3: Market Profitability Ranking

This query ranks markets based on their profit-to-revenue ratio using SQL window functions.

### Insight

The results showed that Southern Africa and Canada exhibited some of the highest profit efficiencies, generating relatively strong profits compared to the revenue earned. This indicates that these markets operate more efficiently and contribute positively to overall profitability.

### Result
<img width="1366" height="734" alt="SQL Query 3 Market Profitability" src="https://github.com/user-attachments/assets/821b7f06-e1e7-49c3-90c6-e3c3b310333c" />



