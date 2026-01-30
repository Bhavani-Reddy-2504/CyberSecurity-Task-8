# SQL Injection Assessment Report  
**Task 8 – Automated SQL Injection Testing**

---

## Target Application
- Name: OWASP Juice Shop
- Type: Intentionally Vulnerable Web Application
- Purpose: Security Testing Practice

---

## Tool Used
- SQLMap (Automated SQL Injection Tool)

---

## Vulnerability Tested: SQL Injection

### Description
SQL Injection is a web application vulnerability that allows attackers to
manipulate backend SQL queries by injecting malicious input. This can lead to
unauthorized access, data leakage, and database compromise if proper input
validation is not implemented.

---

## Testing Methodology

### Parameter Identification
- The search functionality was used to identify a potential injectable
  parameter.
- The URL contained the parameter:
