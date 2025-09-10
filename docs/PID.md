Project Initiation Document (PID)

Project Name: Cooperative Management System in Excel
Version: 1.0
Date: 2025-09-10
Owner: HASIABULAERI ISLAMIC COOP LTD

1. Project Purpose
The purpose of this project is to build a lightweight, Excel-based system to manage the financial and membership records of a cooperative society. The system eliminates manual bookkeeping, improves accuracy, and provides clear dashboards for monitoring contributions, loans, expenses, and balances without requiring advanced coding (no VBA).

2. Project Objectives

Develop a structured Excel workbook to:

Record members’ data.

Track contributions (monthly and weekly breakdowns).

Manage loans and repayments.

Capture expenses with categories.

Maintain an income & expenditure ledger.

Provide reports & dashboards for decision-making.

Ensure the system is scalable, easy to use, and can be version-controlled via GitHub.

3. Scope
In Scope ✅

Member registration and status tracking.

Weekly and monthly contribution tracking.

Loan issuance, balances, and repayments.

Expense categorization.

Automatic income/expenditure summaries.

Pivot-based reporting and dashboards.

Data validation, controls, and protections.

Out of Scope ❌

Advanced accounting (e.g., accrual adjustments).

Multi-branch integration.

Online/mobile access (Excel only, though GitHub can store the file).

Automated notifications (SMS/Email).

| Role               | Responsibility                            | Name/Org              |
| ------------------ | ----------------------------------------- | --------------------- |
| Project Sponsor    | Provides funding & overall direction      | Cooperative Executive |
| Project Manager    | Oversees project execution, documentation | \[You]                |
| Users (Treasurers) | Enter weekly/monthly data, run reports    | Coop Staff            |
| Members            | Beneficiaries of the system               | All Coop Members      |

5. Deliverables

Excel Workbook with the following sheets:

Lists

Members

Contributions

Weekly_Contributions

Loans

Repayments

Expenses

Income_Expenditure

Reports / Dashboard

Documentation (Read Me)

GitHub Repository containing:

/docs/PID.md – This document.

/excel/Coop_Management.xlsx – Main workbook.

/docs/UserGuide.md – End-user guide.

/docs/Changelog.md – Version history.

6. Assumptions & Constraints

Users have Microsoft Excel 2019 or Microsoft 365.

No VBA/macros required (formula-driven only).

Cooperative staff have basic Excel skills.

GitHub will be used for backup, version control, and collaboration.

| Risk                               | Impact | Mitigation                              |
| ---------------------------------- | ------ | --------------------------------------- |
| Incorrect formula editing by users | High   | Lock/protect formula cells              |
| Member IDs entered incorrectly     | Medium | Data validation + lookup errors flagged |
| Data loss (file corruption)        | High   | Use GitHub + regular backups            |
| Users unfamiliar with Excel tables | Low    | Provide user guide & training           |
9. Success Criteria

Cooperative staff can record weekly data within 15 minutes.

Dashboards show up-to-date balances and loan statuses.

Data integrity maintained through validation & protected sheets.

GitHub repository serves as a single source of truth for all versions.

| Name / Role     | Signature | Date |
| --------------- | --------- | ---- |
| Project Sponsor |           |      |
| Project Manager |           |      |
| Treasurer       |           |      |
