# A04:2025 - Cryptographic Failures

## What is it?
Failure to properly protect sensitive data in transit and at rest.

## Example:
Storing passwords in plain text, Using HTTP instead of HTTPS, Weak encryption

## Prevention:
- Use TLS 1.2+ everywhere
- Use strong algorithms: AES-256, SHA-256
- Don't store sensitive data if not needed
- Proper key management
