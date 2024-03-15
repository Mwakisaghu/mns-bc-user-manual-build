# 📦 Configuring Terms of Payment and Payment Days
---

Welcome to the setup guide for terms of payment and payment days in Dynamics 365 Finance! Efficient management of payment terms and due dates is crucial for smooth financial transactions. Let's dive into the setup process:

---

## Setting Up Terms of Payment
---

**Terms of Payment Page:**
- Use the **Terms of payment page** to define payment terms for vendors, customers, purchase orders, and sales orders.
- Consider **Skyworlds'** scenario with a standard vendor payment term of Net 30 days.
  - For example, if an invoice dated November 15 with Net 30 payment term, payment is due by December 15.
- Link terms of payment to payment schedules for calculating due dates.
- If using **cash on delivery (COD)** payment method, select a **main account for cash settlement in the Ledger posting area.**

**Action:** Navigate to **Accounts Payable** > **Payment Setup** > **Terms of Payment**.

[![Terms of payment page screenshot](terms_of_payment_screenshot.png]

---

## Defining Payment Days
---

**Payment Days:**
- Define payment days to calculate due dates, always rounding up to the nearest specified date.
- Payment day can be specified for a day in the week or in the month.

**Action:** Navigate to **Accounts Payable** > **Payment Setup** > **Payment Days**.

---

Follow these steps meticulously to configure your terms of payment and payment days effectively, ensuring seamless financial operations within Dynamics 365 Finance. Happy configuring! 🚀
