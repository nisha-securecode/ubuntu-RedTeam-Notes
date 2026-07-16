# A10:2025 - Mishandling of Exceptional Conditions

## What is it?
Application fails to handle errors, timeouts, or unexpected inputs securely. New in 2025.

## Example:
Verbose error message leaking stack trace and DB credentials
App crashes on invalid input and exposes debug info

## Prevention:
- Catch all exceptions
- Fail securely - show generic error to user
- Don't leak stack traces or sensitive info
- Test for edge cases and failures
