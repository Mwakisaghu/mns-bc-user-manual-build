# Loan Reversal Guide
---

<div class="customized-intro-container" id="introduction">
    <p>
The reversal of attached loans is a crucial process in debt management, allowing for the correction of loan attachments and refunds. This process ensures proper handling of loan reversals and associated transactions.
    </p>
</div>

---

:::info Navigate
## Accessing Loan Reversal
---

Accessing the Loan Reversal Feature in Business Central is simple. Follow these steps:
1. **Login to Business Central:** Use your credentials to log in to your Business Central account.
2. **Navigate to Debt Management Unit:** Once logged in, navigate to the **Loan Activity** section.
- Choose either **New System Recoveries** or **Old System Recoveries**.
- You will see a list - **Loan Attachement, Loan Reapportionment, and Loan Reversal**
3. Select **Loan Reversal** from the list.

Once you've accessed the **Reversals' section**, you can begin managing loans using the features and functionalities provided.
:::
---

### Raising Reversal Cases
---
- The system enables DMU to raise reversal cases from the department.
- To raise a reversal case:
  - Navigate to the Reversals section.
  - Choose **New** to raise a new reversal case.


### Displaying Loan Reversal Details
---
- The system shows comprehensive details for loan reversals, including:
  - Loan number
  - Guarantor member number and name
  - Attached loan amount
  - Amount to be refunded
  - Reapportioned amounts
  - Shares to be reversed
  - Total loan to defaulter

### Automated Reversal of Attached Deposits
- The system automates the reversal of attached deposits to their original position before attachment.
- Ensure adherence to the double entry rule with a specific justification for reversal.

### 7.7. Automatic Reversal with Maker Checker Control
- Automated reversal of attached loans with maker checker control is supported.
- Both principal and interest are reversed separately from guarantors to the defaulter’s loan account.
- Automatic refunds to guarantors are facilitated with maker checker control.

### 7.8. Automatic Crediting of Repaid Funds
- Funds repaid by the guarantor are automatically credited to the guarantor’s FOSA/DEPOSITS account and debited from the guarantor's loan.

### 7.9. Reduction of Defaulter’s Loan Balance
- Funds repaid by the defaulter through reapportionment result in a reduction of the defaulter’s loan balance.

### 7.10. Automated Loan Balance Adjustment
- The total loan balance (interest and principal) is automatically debited to the defaulter's account and credited to the guarantor's account, leaving a nil balance.

### 7.11. Manual Reversal and Refund
- Manual reversal and refund of attached accounts are allowed.
- All reversal transactions are automated to post in the relevant journals.

### 7.12. Approval Workflow for Refund Process
- The system facilitates an approval workflow for the refund process.
- Refund requests are sent from the assistant debt management office to the senior debt management office for approval.
- Approved processes are returned to the ADMO for posting, while rejected transactions are closed.
- Deferred requests are returned to the ADMO for amendment.

### 7.13. Transaction Logging
- Every transaction is logged with a transaction user and unique transaction code specific to the debt management unit.

### 7.14. Automated Notification via SMS
- Members receive automated notifications upon reversal and refund through SMS.
- SMS templates can be edited by the HOD to fit future needs.

### 7.15. Status Update on Reversal
- The system automatically updates the status of members from defaulter to active upon reversal of the account.
- Manual unflagging of reversed accounts is also supported.

### 7.16. Removal of Defaulter Alerts
- All automated defaulter alerts are removed from the account upon reversal.

### 7.17. Retention of Reversal Evidence
- The system retains evidence of reversals of defaulted loans from guarantors to defaulters.
- Reversal transactions include details of the loan reversed, including loan number and Mno.

### 7.18. Interest Calculation and Posting
- Interest due is calculated and posted, and the loan repayment rate on the attached loan is retained pre-closure of the account to the guarantor.

### 7.19. Automated Reversal with Maker Checker Control
- Automated reversal of transactions within the day of posting is supported with maker checker control.

### 7.20. Preservation of Transaction History
- Upon reversal, all previous transactions on the loan account remain in the member’s statement.

### 7.21. Handling of Expired Defaulted Loan Accounts
- The system allows for the reversal of expired defaulted loan accounts.
- This facilitates transactions like loan repayments if a member returns on payroll after the loan repayment period has ended.

### 7.22. Payment of Reversed Defaulted Loans
- Payment of the reversed defaulted loan is facilitated, whether through cash, payroll, or any other repayments allowed by the SACCO.

### 7.23. Approval Request Management
- The system provides the ability to cancel or recall approval requests from the sender.

### 7.24. Unique Transaction Codes
- Each loan payment from defaulters and guarantors is assigned a unique code specific to the debt management unit.

### 7.25. Automated Posting to GL Accounts
- Transactions are automatically posted to the relevant GL accounts, streamlining accounting processes.

### 7.26. Filing of Reversal Schedule in EDMS
- The system allows for the filing of reversal schedules in Electronic Document Management Systems (EDMS) for documentation purposes.

### 7.27. Transaction Descriptions
- A free text box is available to provide descriptions/comments of the transaction on the reversal window.
- This feature is accessible for both the maker and checker.

### 7.28. Journal Entry Posting
- The system enables the posting of journal entries for transactions at the unit with maker checker controls.

### 7.29. Automated SMS Notifications
- Upon reversal, the system automatically sends SMS notifications to defaulters and guarantors, providing details of the reversal.

## Conclusion
The reversal of attached loans is a comprehensive process that ensures accuracy and efficiency in debt management operations. By leveraging the functionalities provided by the system, users can effectively manage loan reversals, refunds, and associated transactions,
