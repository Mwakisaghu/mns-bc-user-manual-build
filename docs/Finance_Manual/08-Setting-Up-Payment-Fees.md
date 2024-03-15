# 📦 Setting Up Payment Fees
---

Payment fees allow you to manage additional charges associated with vendor invoices efficiently. Let's dive into setting up payment fees seamlessly:

## Utilizing Payment Fees
---

Payment fees serve the following purposes:
- Specify additional charges on vendor invoices, such as promissory note issuance fees or vendor bank remittance fees.
- Define fee identifications, bank relations, and fee generation methods.

To create a payment fee:
1. Navigate to **> *Accounts Payable* > *Payment Setup* > *Payment Fee.***
2. Create a new record, specifying whether to charge the Vendor or Ledger in the **Charge** field.
3. If Ledger is selected, choose a main account in the **Main Account** field for ledger posting.
4. Select a valid **Journal Type** for which the fee applies, typically Vendor bank remittance.

[Picture/Screenshot!!!!!!!]

## Defining Payment Fee Specifications
---

You can set up payment fees with various specifications, including:
- Different banks
- Methods of payment
- Remittance types
- Payment specifications
- Currencies
- Time periods
- Amount intervals

Specify payment specifications in the **Payment Specification** field and choose the currency enabling the fee in the **Fee Currency** field. Optionally, determine whether the specification is a percentage or an absolute amount in the **Percentage/Amount** field.

[Picture/Screenshot!!!!!]

## Sales Tax Considerations
---

In cases where sales tax is applicable, the net amount is posted to a ledger account, while the sales tax amount is posted to a sales tax account. Additionally, you can enter fees for selected payment fee setup lines based on the interval between remittance and due dates.

Follow these steps meticulously to configure your payment fees effectively, ensuring accurate management of additional charges within Dynamics 365 Finance.🎉
