#  Enterprise Data Migration System

##  Overview
The Enterprise Data Migration System is a Node.js-based ETL application that simulates real-world legacy-to-cloud database migration. 

It extracts structured data from a legacy schema, applies transformation and normalization logic, loads the data into an optimized schema, and generates validation reports to ensure migration accuracy.

This project demonstrates practical knowledge of SQL, data transformation, and post-migration validation processes.

---

## Tech Stack

- Node.js
- Express.js
- MySQL
- EJS
- Bootstrap

---

##  Key Features

- Extracts data from legacy database
- Applies transformation logic:
  - Name splitting (full name → first & last name)
  - Email normalization (lowercase)
  - Date format conversion
- Loads data into normalized schema
- Detects duplicate records using constraints
- Generates migration summary report
- Compares legacy and migrated record counts

---

## 🗄 Database Schema

### Legacy Table
- id
- full_name
- email
- dob (string format)

### Normalized Table
- user_id (Primary Key)
- first_name
- last_name
- email (Unique)
- dob (DATE type)

---

##  Installation & Setup

1. Clone the repository

2. Install dependencies

3. Configure MySQL database

Create database:
4. Update database credentials in:

5. Run the application

6. Open browser

---

##  Sample Output

- Total legacy records
- Total migrated records
- Successfully migrated count
- Duplicate records skipped

---

##  Learning Outcomes

- Understanding ETL (Extract, Transform, Load)
- Data normalization techniques
- Duplicate detection
- Migration validation strategies
- SQL-based integrity verification

---


##  Future Improvements

- Batch migration processing
- Field-level mismatch reporting
- Hash-based reconciliation
- CSV upload support
- Cloud deployment
