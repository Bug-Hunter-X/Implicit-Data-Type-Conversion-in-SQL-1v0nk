# Implicit Data Type Conversion Bug in SQL

This repository demonstrates a common error in SQL queries: implicit data type conversion. Implicit type conversions can lead to incorrect query results and unexpected behavior. This example showcases the issue and provides a solution.

## Bug Description
The original SQL query implicitly converts data types during a comparison, leading to inaccurate results. This is often subtle and difficult to detect.

## Solution
The solution involves explicit type casting to ensure the comparison is made between data of consistent data types. This eliminates ambiguity and produces reliable results.  The updated query explicitly converts values to the correct type before comparison.

## How to reproduce
1. Create a SQL database with a sample table.
2. Run the `bug.sql` query. Note the unexpected results.
3. Run the `bugSolution.sql` query to see the correct output.