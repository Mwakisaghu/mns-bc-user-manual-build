# Setting Up Finance
---

:::note Business Central
<div class="container">
    <div class="custom-note">
        <h1>General ledger setup and general posting setup.</h1>
        <p>The setup of the general ledger is at the core of financial processes because it defines how you post data. Two pages in particular play an important part in configuring your finance processes: 🤗</p>
    </div>
</div>
:::
---




### 📘 The General Ledger Setup page
---

On the General Ledger Setup page, you specify how to handle certain accounting issues in your company, such as:
- Invoice rounding details
- Address formats
- Financial reporting

### 📘 The General Posting Setup page
---

Similarly, on the General Posting Setup page, you specify how you want to set up combinations of general business and general product posting groups. Posting groups map entities such as customers, vendors, items, resources, and sales and purchase documents to general ledger accounts. You fill in a line for each combination of business posting group and product posting group. But you can also open each line in its own posting setup card. Learn more at Posting Group Setups.

:::tip

If you can't see the fields you're looking for in the General Posting Setup page, use the horizontal scroll bar at the bottom of the page to scroll to the right.
:::

To set default options for the general ledger and other parts of the system. Remember to set up the general ledger for each company you have in Microsoft Dynamics 365 Business Central.

**Tabs:**
- General
- Dimensions
- Background Posting
- Reporting
- Application

To get to the General Ledger Setup:

- Click on the **search icon** 
 at the top right.
- Type **general ledger setup** and hit enter.
- Click on the link that appears.



[PICTURE/SCREENSHOT]

## Exploring the General FastTab:
---

#### Follow these steps:

1. Navigate to the **General FastTab** within your setup menu.
2. Explore each field's purpose and customize settings according to your company's requirements.
3. Ensure to save your configurations for seamless operation.

**The common fields include:**

- **Allow Posting From/Allow Posting To:** Set a date range for posting transactions to prevent entries outside that period. This ensures financial accuracy and control.

- **Local Address Format:** Define how addresses appear on printouts, providing flexibility based on geographical needs and preferences.

- **Local Currency Settings:** Customize settings related to your company's local currency:

    - **LCY Code:** Specify the local currency your company operates with.
    
    - **Rounding Precision:** Define how invoice amounts and unit prices are rounded for clarity and consistency.
    
    - **Decimal Places:** Determine the number of decimal places to display for amounts and unit prices, ensuring precision.
    
    - **Currency Symbol and Description:** Personalize the symbol and description for your local currency, enhancing clarity in financial documents.
    
    - **Tax/VAT Rounding Type:** Specify how tax/VAT calculations are rounded for accurate financial reporting.
    
- **Bank Account Configuration:** Set up bank account numbers and reconciliation preferences:

    - **Bank Account Nos.:** Assign number series for bank accounts, streamlining account management.
    
    - **Bank Rec. Adj. Doc. Nos.:** Define document numbers for bank reconciliation adjustments.
    
    - **Bank Recon. with Auto. Match:** Choose between manual reconciliation or automated matching for bank accounts, based on your workflow preferences.
    
- **Data Validation:** Control data validation during document and journal entry:

    - **Enable Data Check:** Decide whether Business Central validates data input in real-time, ensuring accuracy and integrity in financial transactions.

## Exploring the Dimensions FastTab Setup
---
### Overview:
The Dimensions FastTab allows you to configure global and shortcut dimensions, essential for analysis reports and efficient data entry.

#### Instructions:
1. Navigate to the **Dimensions FastTab**.
2. To set up global dimensions:
    - Select **General** and then choose **Change Global Dimensions**.
3. Global dimensions are the first two shortcut dimensions by default.
4. You can add up to six additional shortcut dimensions for fast entry.

## Exploring the Background Posting FastTab Setup
---
### Overview:
The Background Posting FastTab enables you to schedule general ledger postings using job queue entries, facilitating automated processes.

#### Fields to Configure:
- **Post with Job Queue:** Specify if general ledger documents are posted in the background.
- **Post & Print with Job Queue:** Determine if documents are both posted and printed in the background.
- **Job Queue Category:** Assign a category code for job queue entries related to background posting.
- **Notify on Success:** Choose whether to receive notifications upon successful posting and printing.
- **Report Output Type:** Specify the report output format scheduled with job queue entries for post and print actions.

## Exploring the Reporting FastTab Setup
---
### Overview:
The Reporting FastTab helps configure reporting currencies and account schedules for financial reports.

#### Instructions:
1. Determine if another reporting currency is needed.
2. Specify account schedules for reports like balance sheets and income statements.
3. To generate account schedules:
    - Navigate to **G/L Account Categories** via the Search for Page icon.
    - Select **Process** > **Generate Account Schedules**.

## Exploring the Application FastTab Setup
---
### Overview:
The Application FastTab allows for the configuration of currency rounding tolerance and payment application settings.

#### Fields to Configure:
- **Appln. Rounding Precision:** Define the interval for rounding differences in the local currency.
- **Payment Tolerance:** Specify tolerance settings for payment discounts, warnings, and postings.
- **Max. Payment Tolerance Amount:** Determine the maximum amount by which payments can differ from invoice amounts.
- **Changing Payment Tolerance:**
    - Go to **General Ledger Setup**.
    - Select **Actions** > **Functions** > **Change Payment Tolerance**.
    - Set the tolerance percentage and maximum amount.
    - Click **OK** to apply changes.






