# Day 1

## Date

19 July 2026

## Topics Learned

- What is a database
- What is a table
- What is a row
- What is a column
- Primary Key
- SQL Server installation

## What I Learned

Today I learned that a database is a collection of related data stored electronically. Tables organize data into rows and columns, making it easier to manage and retrieve information using SQL.

A Primary Key in SQL is a column (or a combination of columns) that uniquely identifies each row in a table.
Think of it as a person's passport number or National ID number:
- Every person has a unique passport number.
- No two people should have the same passport number.
- A person cannot have a blank (NULL) passport number.

The same rules apply to a primary key.

## Challenges

I had difficulty connecting SQL Server to SSMS, but after troubleshooting, I was able to connect successfully.

## Questions

- What is the difference between a Primary Key and a Unique Key?
- Why do we use schemas in SQL Server?

## Interview Summary
### Primary Key
- Uniquely identifies each row.
- Cannot be NULL.
- Only one per table.
### Unique Key
- Also enforces uniqueness.
- Can allow NULL values (in SQL Server, typically one NULL).
- Multiple unique keys can exist in a table.
### Schema
- A logical container for database objects.
- Improves organization.
- Makes permission management easier.
- Helps avoid object name conflicts.

## Next Goal

Complete the SQL SELECT statement lessons.
