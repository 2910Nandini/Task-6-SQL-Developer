# Task-6-SQL-Developer
# Data Manipulation
# Objective
Enhance skills in SQL by modifying table structures and managing records through adding columns and deleting specific records based on conditions.
# Project Steps
1. Modify Table Structure
Task: Add and Populate New Columns
● Action: Use the ALTER TABLE statement to introduce new columns.
○ Example Columns:
■ LastUpdated (DATE) – To record when the row was last modified.
■ Status (VARCHAR) – To denote active or inactive records.
● Populate New Columns:
○ Use the UPDATE statement to set initial values or use default values for the new columns.
○ Example: Set Status to "Active" for all existing records.
2. Delete Records Based on Conditions
Task: Remove Records Based on Criteria
● Action: Use the DELETE statement to remove records from the table.
○ Example Conditions:
■ Delete records where Status = "Inactive".
■ Remove records older than a specific date in the LastUpdated column.
● Confirm Deletions:
○ Query the table to ensure that only the intended records were deleted.
○ Optionally, use a SELECT statement with the same condition before deletion to review records.
