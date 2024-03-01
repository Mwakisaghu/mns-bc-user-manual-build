# 📦 Purchase Invoices

:::note Purchase Invoices
<div class="container">
    <div class="custom-note">
        <h1>📦 Mastering Purchase Invoices in Business Central</h1>
        <p>Let's get started with <strong>Dynamics 365 Business Central</strong>. 🚀</p>
    </div>
</div>
:::

## 🛒 Introduction
Purchase invoices play a pivotal role in the procurement process, serving as essential documents for recording and processing purchases. This guide will not only cover the creation and management of purchase invoices but also delve into invoice matching, verification, approval, and handling discrepancies.

### 📝 Recording Purchases with Purchase Invoices
### Accessing Purchase Invoices:

- Navigate to the Purchase Invoices section in Business Central.
- Alternatively use the search bar to locate and access the **Purchase Invoices section.**

### Creating and Posting a Purchase Invoice:

- Begin by clicking on the **New** button to create a new purchase invoice.
- Fill in mandatory fields such as vendor information, invoice date, and invoice number.
- Enter details of purchased items or services, including item numbers, quantities, and costs.

:::tipTips to ensure Accurate Invoincing.

Always ensure that purchase invoices are posted only after receiving items or finalizing service agreements to maintain accuracy in inventory valuation.

:::

### 📋 Invoice Matching and Verification
### Match Invoices with Purchase Orders:
- Match received invoices with corresponding purchase orders and goods receipts to ensure accuracy and completeness.
- Verify invoice details such as quantities, prices, and payment terms against the purchase order and receipt information.

### 🚀 Approval and Payment Process
#### Submit for Approval:

- Submit the invoice for approval by clicking on the **Request for Approval** action.
Approvers review and approve the invoice for payment processing.
#### Process for Payment:

- Process approved invoices for payment within the agreed payment terms.
🛠 Handling Discrepancies and Exceptions
#### Investigate and Resolve:

- Investigate and resolve any discrepancies or exceptions identified during the invoice processing.
Communicate with vendors to address discrepancies and ensure timely resolution.
#### Update Records:

- Update relevant records and documentation to reflect the resolution of discrepancies.

## Posting Purchases
On a purchase document, you can choose between the following posting actions:

- Post.
- Preview Posting.
- Post and Print.
- Post Batch.

When a purchase document is posted, the **vendor's account**, the **general ledger (G/L)** and the **item ledger entries** are updated.
> 
**For each purchase document, a purchase entry is created in the G/L Entry table. An entry is also created in the vendor's account in the Vendor Ledger Entry table and a G/L entry is created in the relevant payables account.**

For each purchase line, as applicable, entries are created in the:

- Item Ledger Entry table if the purchase line is of the Item type.
- G/L Entry table if the purchase line is of the G/L Account type.

In addition, purchase documents are always recorded in the Purch. Recpt. Header and Purch. Inv. Header tables.

- You can always review various ledger entries that are created as a result of postings. Choose **Preview Posting** to validate document and inspect expected ledger entries.

:::tipImportant

When you post a purchase order for items, you can create both a receipt and an invoice. These can be done simultaneously or independently. You can also create a partial receipt and a partial invoice by completing the Qty. to Receive and Qty. to Invoice fields on the individual purchase order lines before you post. Note that you cannot create a purchase invoice from a purchase order for products or services that have not been received. That is, before you can invoice, you must have recorded a receipt, or you must choose to receive and invoice at the same time.
:::

You can either **post** or **post and print**. If you choose to post and print, a report is printed when the order is posted.

### Viewing ledger entries
- When the posting is completed, the posted purchase lines are removed from the order. A message tells you when the posting is completed. 
- You'll be able to see the posted entries in various pages, including the Vendor Ledger Entries, G/L Entries, Item Ledger Entries, Resource Ledger Entries, Purchase Receipts, and Posted Purchase Invoices pages.

> ***In most cases, you can open ledger entries from the affected card or document. For example, on the Vendor Card page, choose the Entries action.***