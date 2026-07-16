# A05:2025 - Injection

## What is it?
Sending untrusted data to an interpreter. SQL, NoSQL, OS Command, XSS.

## Example:
SQLi: `' OR 1=1--`
XSS: `<script>alert(document.cookie)</script>`
Command: `; cat /etc/passwd`

## Prevention:
- Use Prepared Statements / Parameterized Queries
- Input validation and sanitization
- Use ORM frameworks
- Output encoding for XSS
