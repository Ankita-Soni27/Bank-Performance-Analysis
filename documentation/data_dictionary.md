# Data Dictionary

## accounts.csv

| Column | Description |
|---|---|
| account_id | Unique account identifier |
| customer_id | Customer identifier |
| account_type | Current, Salary or Savings |
| account_open_date | Date the account was opened |
| account_status | Active, Closed or Dormant |
| balance | Account balance |
| branch_id | Branch identifier used to connect to branches.csv |

## branches.csv

| Column | Description |
|---|---|
| branch_id | Unique branch identifier |
| branch_name | Branch name |
| city | Branch city |
| state | Branch state |
| region | Regional grouping |

## transactions.csv

| Column | Description |
|---|---|
| transaction_id | Unique transaction identifier |
| account_id | Account associated with the transaction |
| transaction_date | Date of transaction |
| transaction_type | Credit or Debit transaction type |
| amount | Transaction value |
| payment_method | ATM, IMPS, NEFT, POS, RTGS or UPI |
| merchant | Merchant / counterparty name |
| transaction_status | Success, Failed, Pending or UNKNOWN |
