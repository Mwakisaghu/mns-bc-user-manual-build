# 📦 Configuring Cash Discounts
---

Welcome to the Cash Discounts Configuration guide in Dynamics 365 Finance! Cash discounts provide opportunities for savings on vendor invoices, ensuring efficient financial management. Let's explore how to set up cash discounts effectively:

---

## Skyworld's Cash Discount Strategy
---
Skyworld offers cash discounts to incentivize prompt payment of vendor invoices. Here's their discount structure:

- 5D10%: 10% discount if paid within five days.
- 10D5%: 5% discount if paid within ten days.
- 14D2%: 2% discount if paid within 14 days.
The discounts occur sequentially as the due date approaches, with only one discount being granted.

## Setting Up Cash Discounts
---

- ### Cash Discounts Page:

- Specify cash discount codes and their corresponding next discount codes.
- For instance, select the 10D5% code as the next discount code for the 5D10% code.

> ***Action: Navigate to Accounts Payable > Payment Setup > Cash Discounts.***

[Picture/Screenshot!!!!!]


## Cash-Discount Administration Setup
---
- ### Accounts Payable Parameters:

- Configure how overpayments or underpayments are handled when cash discounts are not deducted.
- Choose between **Unspecific** or **Specific** options based on your preference.

> ***Action: Go to Accounts Payable > Setup > Accounts Payable Parameters > Settlement Tab.***

[Picture/Screenshot!!!!]

## Example Scenario
---
- ### Understanding the Options:

Consider a vendor invoice total of 105.00 USD with a cash discount of 10.50 USD.
If the Cash-discount administration parameter is set to **Unspecific,** the difference of 0.50 USD is posted to the ledger account for cash discount differences.
If set to **Specific,** the difference is posted to the vendor's cash discount account.

## Additional Configuration
---
- ### Sales Tax Consideration:

Configure whether cash discounts are calculated based on the amount including sales tax.
Enable the "Cash discount is calculated on amount including sales tax" option in General ledger parameters under the Sales tax tab.

> ***Action: Navigate to General Ledger > Setup > General Ledger Parameters > Sales Tax Tab.***


Follow these steps diligently to configure your cash discounts effectively, ensuring streamlined vendor invoice payments within Dynamics 365 Finance. Happy configuring! 🚀