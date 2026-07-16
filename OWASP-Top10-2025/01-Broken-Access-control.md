A01:2025 - Broken Access Control

## What is it?
Access controls enforce what a user can and cannot do. When broken, attackers can access other users' data, admin functions, or internal systems. Now includes SSRF, BOLA, BFLA.

## Example:
1. Changing `user_id=100` to `user_id=101` in URL
2. Calling `/admin/deleteUser` API as a normal user
3. SSRF: `url=http://localhost:8080/admin`

## Prevention:
- Deny by default
- Enforce access control on every request server-side
- Test for BOLA/BFLA in APIs
- Validate and whitelist URLs to prevent SSRF
