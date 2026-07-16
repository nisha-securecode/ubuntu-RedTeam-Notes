# A03:2025 - Software Supply Chain Failures

## What is it?
Vulnerabilities in 3rd party components, libraries, CI/CD pipelines, and build processes. Expanded from "Vulnerable Components".

## Example:
Malicious NPM package, Compromised GitHub action, Old Log4j version with RCE

## Prevention:
- Maintain SBOM - Software Bill of Materials
- Scan dependencies regularly with Snyk/Dependabot
- Verify package signatures
- Secure CI/CD pipelines
