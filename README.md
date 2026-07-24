# Database Fundamentals & Log Analysis

## Project Overview
This project focused on two core QA-adjacent skills: navigating and analyzing data through the Linux command line, and querying relational databases using SQL. The work combined server log analysis (identifying and filtering specific records within raw log files) with structured SQL queries against a ride-sharing dataset to answer real business questions.

## What I Did
- Used Linux terminal commands (`grep`, `mkdir`, `wc`) to search, filter, and organize server log files by IP address and HTTP status codes.
- Applied regular expressions to isolate specific log entries (e.g., HTTP 400 and 500 error codes) without false positives.
- Wrote SQL queries using `COUNT`, `DISTINCT`, `GROUP BY`, `HAVING`, `CASE`, `LIKE`, and `INNER JOIN` to analyze a ride-sharing dataset — including counting unique vehicles, filtering companies by fleet size, and classifying data with conditional logic.
- Applied date filtering and type conversion within SQL queries to ensure accurate temporal comparisons.

## Skills Demonstrated
- Linux Command Line
- Regular Expressions (grep)
- Log File Analysis
- SQL (PostgreSQL)
- Data Aggregation (COUNT, GROUP BY, HAVING)
- Conditional Logic (CASE)
- Table Joins (INNER JOIN)

## Tools
Linux Terminal, PostgreSQL, SQL

## Status
✅ Completed — Approved

## Reviewer Feedback (Summary)
Approved, with positive feedback on command-line and SQL comprehension. Improvement note: when counting unique items, `COUNT(DISTINCT column)` is more accurate than `COUNT(*)`, which can overcount duplicated records.
