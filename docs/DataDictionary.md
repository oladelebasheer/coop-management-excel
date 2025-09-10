# 📊 Data Dictionary – Cooperative Management System

This document explains the structure of each sheet.

---

## Members (tblMembers)
| Column       | Description                        | Example   |
|--------------|------------------------------------|-----------|
| Member ID    | Unique code for each member        | M001 |
| Full Name    | Member’s full name                 | Jane Doe |
| Gender       | M/F                                | F |
| Phone        | Contact number                     | 08012345678 |
| Email        | Email address                      | jane@example.com |
| Date Joined  | Date member joined                 | 2025-01-10 |
| Status       | Active / Inactive                  | Active |

---

## Contributions (tblContrib)
| Column          | Description                        | Example |
|-----------------|------------------------------------|---------|
| Date            | Contribution date                  | 2025-02-01 |
| Member ID       | Lookup key to Members              | M001 |
| Full Name       | Auto-filled from Members           | Jane Doe |
| Amount Contrib. | Amount contributed                 | 2000 |
| Payment Method  | Cash, Transfer, Mobile Money, etc. | Cash |
| Notes           | Free-text notes                    | January dues |

---

## Weekly_Contributions (tblWeekly)
| Column                | Description                         |
|------------------------|-------------------------------------|
| Date                   | Contribution date                  |
| Week No.               | Week number (auto or dropdown)     |
| Member ID              | Lookup to Members                  |
| Full Name              | Auto-filled                        |
| Savings – Shares       | Contribution to shares             |
| Savings – Normal       | Normal savings                     |
| Admin/Development      | Admin/development levy             |
| Return for Loan        | Loan repayment                     |
| Building               | Building fund                      |
| Deposit                | Misc deposits                      |
| Bank Charges           | Fees collected from members        |
| Legal Charges          | Legal levy                         |
| Passbook Purchase      | Fee for passbook                   |
| Loan ID (for returns)  | To map repayment to loan           |
| Total Contribution     | Auto-sum of all categories         |

---

## Loans (tblLoans)
| Column                 | Description                     |
|------------------------|---------------------------------|
| Loan ID                | Unique ID (e.g., L001)         |
| Date Issued            | Loan issue date                |
| Member ID              | Borrower’s ID                  |
| Full Name              | Auto-filled from Members       |
| Loan Amount            | Principal amount               |
| Interest Rate (%)       | Loan interest rate             |
| Repayment Period (Mo.) | Months to repay                |
| Total Repayable        | Auto: Loan Amount × (1+Rate)   |
| Balance                | Auto: Total – repayments       |

---

## Repayments (tblRepayments)
| Column       | Description                          |
|--------------|--------------------------------------|
| Date         | Repayment date                       |
| Loan ID      | Loan being repaid                    |
| Member ID    | Borrower’s ID                        |
| Full Name    | Auto-filled from Members             |
| Amount Paid  | Repayment amount                     |
| Payment Method | Cash, Transfer, Mobile Money, etc. |
| Receipt No.  | Reference/receipt number             |
| Notes        | Notes                                |

---

## Expenses (tblExpenses)
| Column         | Description                     |
|----------------|---------------------------------|
| Date           | Expense date                    |
| Expense Category | Rent, Utilities, Salaries, etc.|
| Description    | Details                         |
| Payment Method | Cash/Bank/etc.                  |
| Amount         | Expense amount                  |
| Approved By    | Who authorized                  |
| Notes          | Notes                           |

---

## Income_Expenditure (tblLedger)
| Column     | Description                          |
|------------|--------------------------------------|
| Date       | Entry date                          |
| Description| Transaction description             |
| Income     | Summed inflows from contributions   |
| Expenditure| Summed outflows from expenses       |
| Balance    | Running balance                     |
