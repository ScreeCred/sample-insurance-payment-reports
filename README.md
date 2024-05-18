# sample-insurance-payment-reports
This repo contains both the JSON and CSV formats for the insurance payment report we expect from our partners

# Description of each data points
1. Policy ID: Unique identifier for each insurance policy.
2. Policyholder Name: Name of the policyholder.
3. Policyholder Address: Address of the policyholder.
4. Policyholder Phone Number: Phone number of the policyholder.
5. Policyholder Email: Email address of the policyholder.
6. Policy Start Date: Date when the insurance policy coverage starts (YYYY-MM-DD format).
7. Policy End Date: Date when the insurance policy coverage ends (YYYY-MM-DD format).
8. Policy Type: Type of insurance policy. Possible values:
    * Auto (for automobile insurance policies)
9. Payment ID: Unique identifier for each payment transaction.
10. Payment Date: Date when the payment was made (YYYY-MM-DD format).
11. Payment Amount: Amount of the payment made (numeric, in USD).
12. Payment Status: Status of the payment transaction. Possible values:
    * Paid
    * Unpaid
    * Partially Paid
    * Overdue
13. Payment Method: Method used for making the payment. Possible values:
    * Credit Card
    * Debit Card
    * Bank Transfer
    * Check
    * Cash
14. Payment Frequency: Frequency of payments. Possible values:
    * Monthly
    * Quarterly
    * Semi-Annually
    * Annually
15. Due Date: Date by which the payment is due (YYYY-MM-DD format).
16. Policy Premium Amount: Total premium amount for the insurance policy (numeric, in USD).
17. Outstanding Balance: Remaining balance due on the policy (numeric, in USD).
18. Late Payment Fees: Fees charged for late payments (numeric, in USD).
19. Grace Period: Number of days of grace period allowed before a payment is considered late (integer, in days).
20. Last Payment Date: Date of the last payment made (YYYY-MM-DD format).
21. Next Payment Due Date: Date when the next payment is due (YYYY-MM-DD format).
22. Days Overdue: Number of days the payment is overdue (integer, in days).
23. Penalty Charges: Additional charges or penalties applied for late payments (numeric, in USD).
24. Discounts Applied: Discounts applied to the premium amount (numeric, in USD).
25. Renewal Status: Current status of policy renewal. Possible values:
    * Renewed
    * Not Renewed
26. Cancellation Date: Date when the policy was canceled (YYYY-MM-DD format). Leave blank if not canceled.
27. Reason for Cancellation: Reason provided for canceling the policy. Specify "Not Applicable" if not canceled.
28. Collection Status: Status of the policy in collections. Possible values:
    * In collection
    * Not in collection
    * Pending collection
    * Paid in full (from collections)
    * Settled
