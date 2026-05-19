# Pharmacy-Management-System
Developed a Pharmacy Management System using MySQL to manage and organize pharmacy-related records efficiently. Performed database design, DDL and DML operations, joins, constraints, and data manipulation across multiple related tables as part of a collaborative 5-member team project.

About This Project

This is a Pharmacy Management System database project using SQL.
It helps efficiently manage medicines, customers, doctors, prescriptions, and billing and extracts insights using advanced SQL queries like joins, subqueries, views, and aggregations.

Database Tables

1)Medicine-Stores medicine details.

i) m_id (Primary Key)
ii) name
iii) brand
iv) price
v) expiry
vi) stock

2)Customer-Stores customer details.

i) c_id (Primary Key)
ii) name
iii) phone
iv) address

3)Doctor-Stores doctor details.

i) d_id (Primary Key)
ii) name
iii) specialization
iv) phone

4)Prescription-Connects doctors, customers, and medicines.

i) p_id (Primary Key)
ii) c_id (Foreign Key)
iii) d_id (Foreign Key)
iv) m_id (Foreign Key)
v) prescription_date
vi) dosage
vii) duration

5)Bill-Stores billing information.

i) b_id (Primary Key)
ii) c_id (Foreign Key)
iii) p_id (Foreign Key)
iv) bill_date
v) total_amt
vi) payment_method

Features & SQL Concepts Used

i)   Aggregate Functions
ii)  Joins (INNER, LEFT)
iii)   Subqueries (nested & correlated)
iv)   Views (Doctor workload analysis)
v)   Filtering (LIKE, BETWEEN, IN)
vi)   Date functions
vii)   Group By & Having

Insights Generated

This system assists in analyzing:

i)   Pharmacy revenue trends
ii)   Doctor performance metrics
iii)   Medicine demand and expiry management
iv)   Customer purchasing habits
v)   Daily and monthly sales trends

Technologies Used

i)   SQL (Oracle-style syntax)
ii)   Database Design Principles
iii)   Relational Schema (PK/FK)
iv)   Views & Subqueries

How to Run

1.  Open SQL editor (compatible with Oracle / MySQL)
2.  Run table creation scripts
3.  Insert sample data
4.  Execute queries for analysis
