---
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# 🏛️ Bank Account Management

## Bank Accounts Overview

Bank accounts in Otutu are your digital connection to your actual bank accounts - they're the bridge between your real-world banking and your accounting system. Think of them as secure containers that track every dollar flowing in and out of your business, automatically keeping your financial records in sync with your bank statements.

### Why This Matters

Without proper bank account management, you'd spend countless hours manually entering transactions, risk missing important financial activities, and never have a clear picture of your actual cash position. Good bank account management means:

* Always knowing your true cash balance
* Automatic transaction importing saves hours of data entry
* Easy reconciliation prevents errors and fraud
* Multi-currency support for international business
* Professional financial reporting based on real bank data

### Prerequisites

* Banking module access permissions
* Bank account information (account numbers, bank details)
* Company setup completed

### Step-by-Step Instructions

#### 1. Navigate to Bank Accounts

📸 **Image Placeholder:** Bank accounts list page screenshot

1. Click **"Banking"** in the left navigation
2. Select **"Bank Accounts"** from the dropdown menu
3. View all your connected bank accounts in one place

#### 2. Create New Bank Account

📸 **Image Placeholder:** New bank account creation form screenshot

1. Click **"New Bank Account"** button
2. **Account Type Selection:** Choose from Depository, Investment, Credit, or Loan accounts

| Type       | Description                                 |
| ---------- | ------------------------------------------- |
| Depository | Checking and savings accounts (most common) |
| Investment | Investment and brokerage accounts           |
| Credit     | Credit cards and lines of credit            |
| Loan       | Loans and other debt accounts               |

#### 3. Configure Account Information

📸 **Image Placeholder:** Account configuration screenshot

* **Account Name:** Descriptive name (e.g., "Main Business Checking")
* **Account Number:** Enter actual bank account number
* **Currency:** Select account currency (required for multi-currency businesses)
* **Default Account:** Mark as default if this is your primary account

#### 4. Account Subtype Configuration

📸 **Image Placeholder:** Account subtype configuration screenshot

* System automatically shows subtypes based on account type:
  * Depository: Current Assets, Cash Equivalents
  * Credit: Current Liabilities, Credit Cards
  * Loan: Long-term Liabilities, Loans Payable

#### 5. View Account Balances

📸 **Image Placeholder:** Account balances dashboard screenshot

* See real-time balances for all accounts
* Balances formatted with currency codes
* Default accounts show a lock icon for easy identification

#### 6. Connect Bank Feeds (Optional)

📸 **Image Placeholder:** Bank feed connection screenshot

1. Select your bank from supported institutions
2. Use Plaid integration for secure connection
3. Import transactions automatically (daily)
4. Optionally, import up to 2 years of historical data

#### 7. Manage Connected Accounts

📸 **Image Placeholder:** Connected accounts management screenshot

* **Toggle Import:** Start/stop automatic transaction importing
* **Refresh Data:** Manually trigger imports
* **View Balance:** See current bank balance
* **Disconnect:** Remove bank connection if needed

#### 8. Multi-Currency Bank Accounts

📸 **Image Placeholder:** Multi-currency account setup screenshot

* Create separate accounts for each currency
* Set appropriate currency code during account creation
* System handles automatic currency conversion for reporting

#### 9. Transaction Management

**Automatic Transaction Import**

* Transactions import automatically from connected accounts
* Categorized based on bank descriptions
* Duplicates detected and merged automatically

**Manual Transaction Entry**

* Add transactions manually for non-connected accounts
* Record deposits, withdrawals, and transfers
* Attach receipts and supporting documentation

**Starting Balance Setup**

* Set starting balance when connecting a new account
* System creates opening balance transaction to ensure books balance

#### 10. Account Reconciliation

📸 **Image Placeholder:** Reconciliation interface screenshot

* **Monthly Process:** Import transactions, match entries, investigate differences, adjust records, confirm balance
* **Reconciliation Tools:** Automatic matching, manual override, reconciliation reports for audit

### Tips and Best Practices

#### Account Organization

* Use descriptive names (e.g., "Business Checking")
* Separate business and personal accounts
* Group similar accounts for better reporting

#### Security Considerations

* Monitor account activity weekly
* Limit who can view/modify accounts
* Use secure connections for bank feeds

#### Multi-Currency Management

* Separate accounts for different currencies
* Convert foreign balances regularly
* Monitor exchange rates for favorable conversions

#### Performance Optimization

* Connect only active accounts
* Archive unused accounts
* Process imports during off-peak hours

### Common Use Cases

#### Small Business Setup

* Primary Checking: Main operations account
* Savings Account: Emergency fund, tax reserves
* Credit Card: Business expenses and rewards

#### International Business

* Multi-currency accounts for each currency
* Foreign bank accounts
* Regular currency conversion transfers

#### Non-Profit Organizations

* Operating account for daily expenses
* Restricted funds for donations
* Investment accounts for endowment/reserve funds
