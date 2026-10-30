# Data Dictionary

| Variable | Type | Description |
|---|---|---|
| age | Integer | Borrower age in years, restricted to 18-75 |
| monthly_income | Float | Synthetic monthly disposable income |
| loan_amount | Float | Synthetic outstanding loan amount |
| dti | Float | Debt-to-income ratio, bounded between 0 and 1 |
| credit_utilisation | Float | Used share of available revolving credit |
| delinquencies_12m | Integer | Recent delinquency events, from 0 to 3 |
| default_flag | Binary | 1 for default and 0 for non-default |

No variable contains real customer information.
