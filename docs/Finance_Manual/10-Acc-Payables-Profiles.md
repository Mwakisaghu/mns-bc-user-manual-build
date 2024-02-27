# 📝 Setting Up Accounts Payable Posting Profiles

Posting profiles play a crucial role in defining summary accounts for vendors, ensuring accurate and efficient financial management. Let's dive into configuring accounts payable posting profiles:

## Understanding Posting Profiles

Posting profiles define summary accounts for vendors and can be assigned to:
- A single vendor
- Groups of vendors
- All vendors

When posting vendor transactions automatically, Finance follows a specific order:
1. Uses the posting profile line for the vendor, if available.
2. If no specific line exists for the vendor, it uses the line specified for the vendor group.
3. If neither exists, the posting profile line for all vendors is used.

## Setting Up Vendor Posting Profiles

To create vendor posting profiles:
1. Navigate to > ****Accounts Payable* > *Setup* > *Vendor Posting Profiles*.***
2. Configure multiple posting profiles if transactions for all vendors are processed together.

[Picture/Screenshot!!!!!!!]

## Handling Vendor Invoices

- If using an invoice register and approval journal, invoices are recorded as arrivals until approved and then transferred to the vendor summary account.
- If not using an invoice register, invoices are updated directly in the vendor summary account.

For detailed procedures on daily Accounts Payable tasks, refer to the documentation.

## Setting Default Posting Profile

After creating posting profiles, set a default profile in > ****Accounts Payable* > *Setup* > *Accounts Payable Parameters**** under the ***Ledger and Sales Tax*** tab.
