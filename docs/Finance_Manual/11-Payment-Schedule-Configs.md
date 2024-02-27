# 📅 Payment Schedule Configuration in Dynamics 365 Finance

In Dynamics 365 Finance, the setup of payment schedules plays a pivotal role in managing customer payments efficiently. Before delving into the configuration process, it's important to note that certain payment setups are shared between Accounts Payable and Accounts Receivable, including payment days, payment schedules, terms of payment, and cash discounts.

## Understanding Payment Schedules

Payment schedules enable the acceptance of customer payments in installments, providing flexibility and convenience. Here's what you need to define when setting up a payment schedule:

- Number of installments
- Amount of each installment
- Due date of each installment

A payment schedule comprises consecutive payments in specified time intervals, which can either be a set amount or a specified number of payments with equal amounts.

### Allocation Methods

The allocation method determines how payments are distributed within the payment schedule. Here are the available allocation methods:

- **Total:** Pays the total outstanding amount on the invoice.
- **Fixed Amount:** Specifies a fixed amount for each payment.
- **Fixed Quantity:** Divides the total amount into a fixed number of payments.
- **Specified:** Specifies a certain amount due on each specified payment date.

## Configuring Payment Schedules

To set up a payment schedule, follow these steps:

1. **Select Allocation Method:** Depending on the allocation method chosen, different fields are enabled on the General and Payment lines FastTabs.

2. **Define Payment Interval:** Specify the payment interval (Days, Months, or Years) on the General FastTab.

3. **Sales Tax Allocation:** Use the Sales tax allocation list to distribute the sales tax amount to the payment schedule installments if necessary.

4. **Define Payment Lines:** On the Payment lines FastTab, define the line information for the payment schedule, including the quantity and amount for each installment. 

5. **Set Amount or Quantity:** Enter the time interval for each installment in the Quantity field and the value of the installment in the Amount in transaction currency field. Select whether the value entered is a percent or an absolute amount.

6. **Complete Setup:** Save the payment schedule configuration.

## Terms of Payment and Payment Days Configuration

In Dynamics 365 Finance, the setup of terms of payment and payment days is crucial for managing accounts receivable and accounts payable efficiently. These configurations ensure accurate calculation of due dates and streamline payment processes. Let's explore how to set up terms of payment and payment days effectively:

## Terms of Payment

Terms of payment define the conditions under which a customer or vendor must make payment. They are shared between accounts receivable and accounts payable. Follow these steps to specify terms of payment:

1. **Define Terms of Payment:** Go to the Terms of payment page to set up payment terms for customers and vendors.
2. **Assign to Customers or Sales Orders:** Specify terms of payment for customers on the Customers page or for sales orders on the Sales order page.

## Payment Days

Payment days determine the day used for calculating the due date of invoices. This setting helps in suggesting invoices for payment proposal. Here's how to configure payment days:

1. **Access Payment Days Setup:** Navigate to Accounts Receivable > Payments Setup > Payment Days.
2. **Define Payment Days:** Specify the payment day, which can be a specific day of the week or month, to calculate due dates accurately.

Ensure to enter the date as a numeral (e.g., 10) rather than an ordinal number (e.g., 10th) for clarity and consistency.

[Picture/Screenshot!!!!!!!]

By setting up terms of payment and payment days meticulously, you can ensure prompt payments from customers and vendors, facilitating smoother financial transactions within Dynamics 365 Finance.

