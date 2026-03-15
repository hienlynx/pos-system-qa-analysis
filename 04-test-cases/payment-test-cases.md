| Test Case ID | Scenario                  | Steps                   | Expected Result                           |
| ------------ | ------------------------- | ----------------------- | ----------------------------------------- |
| TC-PAY-01    | Successful card payment   | Checkout → Pay by card  | Payment success and transaction completed |
| TC-PAY-02    | Payment failure           | Checkout → Invalid card | Transaction not completed                 |
| TC-PAY-03    | Duplicate payment attempt | Retry payment           | System prevents double charge             |
