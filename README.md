# Task 8 – SQL Injection Testing Using SQLMap

## Overview
This task focuses on performing automated SQL Injection testing using SQLMap
on a deliberately vulnerable web application. The objective is to understand
how SQLMap is used to identify injectable parameters and attempt database
enumeration in a controlled and ethical testing environment.

## Tools Used
- Kali Linux
- SQLMap
- Google Chrome
- OWASP Juice Shop (Vulnerable Web Application)

## Target Application
- Application: OWASP Juice Shop
- URL: https://juice-shop.herokuapp.com/

## Objective
- Identify potential SQL Injection points
- Test parameters using SQLMap
- Attempt database and table enumeration
- Analyze and document results

## Methodology
1. Accessed the OWASP Juice Shop application.
2. Identified the search parameter (`q`) from the URL.
3. Used SQLMap to test the parameter for SQL Injection.
4. Attempted database enumeration using SQLMap.
5. Attempted table and user data extraction.
6. Observed application behavior and SQLMap responses.
7. Documented findings with screenshots and analysis.

## Files Included
- `analysis.txt` – Observations and testing outcomes
- `report.md` – Detailed SQL Injection assessment report
- `screenshots/` – Evidence of SQLMap execution and results

## Outcome
This task provided practical experience with SQLMap and demonstrated how
application-side protections can limit automated SQL Injection exploitation.
