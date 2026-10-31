# Data Dictionary

| Variable | Type | Description |
|----------|----------|-------------|
| `age` | Integer | Borrower age in years, restricted to the range 18–75 |
| `monthly_income` | Float | Synthetic monthly disposable income |
| `loan_amount` | Float | Synthetic outstanding loan amount |
| `dti` | Float | Debt-to-income ratio, bounded between 0 and 1 |
| `credit_utilisation` | Float | Proportion of available revolving credit currently in use |
| `delinquencies_12m` | Integer | Number of delinquency events during the previous 12 months |
| `default_flag` | Binary | Default indicator (1 = default, 0 = non-default) |
| `true_pd` | Float | True probability of default used during synthetic data generation |

## Notes

- All observations are synthetically generated.
- No real customer, banking, or personal information is included.
- The variable `true_pd` is used only for model evaluation and is not included as a predictor in the modelling process because such information would not be observable in practice.
