# Business Insights — Bank Performance Analytics

## Full Source Data Summary

- Accounts: 20,050
- Branches: 200
- Transactions: 501,000
- Account balance: ~₹5.03B
- Transaction value: ~₹25.05B
- Active accounts: 59.5%
- Successful transactions: 60.0%

## Account Status

| Status | Accounts |
|---|---:|
| Active | 11,936 |
| Dormant | 4,058 |
| Closed | 4,056 |

## Account Type

Salary, Savings and Current accounts are all material parts of the portfolio and have similar record volumes.

## Transaction Status

| Status | Transactions |
|---|---:|
| Success | 300,446 |
| Failed | 100,257 |
| Pending | 100,197 |
| UNKNOWN | 100 |

## Payment Methods

IMPS has the largest total transaction value at about ₹4.21B. The six payment methods are otherwise relatively close in total value.

## Data Quality

The source data includes mixed capitalization in Region and Transaction Type values, a small number of unknown transaction statuses, missing account-to-transaction matches, and some accounts without a matching branch record. These should be handled explicitly in production reporting.
