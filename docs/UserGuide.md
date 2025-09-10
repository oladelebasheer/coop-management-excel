# 👩‍💻 User Guide – Cooperative Management System (Excel)

This guide explains how to use the Excel workbook.

---

## 1. Setup
1. Download and open `excel/Coop_Management.xlsx`.
2. Enable editing if prompted.
3. Do not delete or rename sheets.

---

## 2. Sheets Overview
- **Members** → Register members (unique IDs, status).
- **Contributions** → Record general contributions.
- **Weekly_Contributions** → Record detailed weekly savings/fees.
- **Loans** → Issue loans and track balances.
- **Repayments** → Capture loan repayments.
- **Expenses** → Record cooperative outflows.
- **Income_Expenditure** → Ledger showing net balance.
- **Reports** → Dashboards, PivotTables, KPIs.

---

## 3. Data Entry Steps
1. **Add Members** → Enter Member ID, Name, Status.
2. **Record Contributions** → Enter Date, Member ID, Amount, Payment Method.
3. **Weekly_Contributions** → Fill in savings, shares, loan returns, etc.
4. **Loans** → Enter Loan ID, Date, Member ID, Loan Amount, Interest %.
5. **Repayments** → Enter payments (must match Loan ID).
6. **Expenses** → Record Rent, Utilities, Bank Charges, etc.

---

## 4. Reports
- Refresh PivotTables: Right-click → Refresh.
- Use slicers for filtering by week, member, or category.
- KPIs auto-calculate totals (savings, loans, expenses).

---

## 5. Controls
- Lookup errors display “Not Found”.
- Overdue loans flagged via conditional formatting.
- Formula cells are locked/protected.

---

## 6. Best Practices
- Enter data weekly to avoid backlog.
- Keep Member IDs and Loan IDs consistent.
- Back up workbook by pushing to GitHub regularly.
