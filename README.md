# Banking System Database Design with Oracle APEX

This project showcases the design and implementation of a **relational database for a banking system** using [Oracle APEX](https://apex.oracle.com).

## 📌 Project Overview

The system includes a full database schema that represents a real-world banking environment. It is built to demonstrate practical data modeling skills, covering a variety of essential banking components.

---

## 📂 Key Features

- ✅ Structured SQL table creation
- ✅ Data insertion statements for testing
- ✅ Realistic SQL queries for:
  - Customer management
  - Employee and dependent tracking
  - Account and transaction handling
  - Loans and installments

---

## 🏛️ Tables Included

The project covers 16 main tables:
- `Bank`
- `Branch_ba`
- `Employee`
- `Emp_MobileNo`
- `Dependent_Emp`
- `Customers`
- `Cust_Mobile`
- `Server`
- `Cust_Account`
- `Account_Movement`
- `Move_typeCode`
- `Loan`
- `L_Payment`
- `Installment`
- `Installment_details`
- `Installment_Payments`

---

##  Sample Queries

```sql
-- Example 1: Find employees with specific salary and job
SELECT Salry, job_name 
FROM Employee 
WHERE Salry < 9500 AND job_name = 'Customers service';

-- Example 2: List customer email addresses starting with 'M'
SELECT Cus_id, Cus_Emile 
FROM Customers 
WHERE Fname LIKE 'M%';
