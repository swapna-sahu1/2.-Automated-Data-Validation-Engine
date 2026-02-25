# Automated Data Reconciliation Engine

##  Overview
The Automated Data Reconciliation Engine is a Node.js application designed to validate and verify database migrations by comparing legacy and migrated datasets.

It performs record-level validation, detects missing records, and generates discrepancy reports in CSV format to ensure post-migration data integrity.

This project simulates enterprise-grade migration verification workflows.

---

## Tech Stack

- Node.js
- Express.js
- MySQL
- EJS
- json2csv
- Bootstrap

---

## Key Features

- Compares legacy and migrated datasets
- Detects:
  - Missing records
  - Email mismatches
- Generates CSV discrepancy report
- Displays reconciliation summary dashboard
- Validates record counts

---

## Database Structure

### Legacy Table
- id
- full_name
- email
- dob

### Migrated Table
- user_id
- first_name
- last_name
- email
- dob

---

##  Installation & Setup

1. Clone repository
2. Install dependencies
3. Create MySQL database
4. Update credentials in:
5. Run application
6. Open browser
---

##  Output

- Total legacy records
- Total migrated records
- Missing record count
- CSV discrepancy report generated automatically

---

##  Example CSV Report

| email           | issue                     |
|-----------------|--------------------------|
| alex@email.com  | Missing in migrated table |

---

##  Learning Outcomes

- Post-migration data validation
- Record-level reconciliation logic
- CSV report generation
- SQL-based dataset comparison
- Enterprise data integrity verification

---

## Resume Highlight

Developed an automated reconciliation engine to validate migrated datasets by detecting missing and inconsistent records and generating structured CSV discrepancy reports.

---
## Future Improvements

- Field-level comparison validation
- Hash-based integrity checking
- Downloadable CSV button
- UI-based dataset upload
- Audit logging system
