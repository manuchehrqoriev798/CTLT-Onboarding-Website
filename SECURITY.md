# Security Policy

## Reporting Security Issues

If you believe you have found a security vulnerability in this project, please report it to us through coordinated disclosure.

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, please send an email to [your-email-address].

Please include as much of the information listed below as you can to help us better understand and resolve the issue:

* Type of issue (e.g., exposed API key, SQL injection, etc.)
* Full paths of source file(s) related to the manifestation of the issue
* The location of the affected source code (tag/branch/commit or direct URL)
* Any special configuration required to reproduce the issue
* Step-by-step instructions to reproduce the issue
* Proof-of-concept or exploit code (if possible)
* Impact of the issue, including how an attacker might exploit the issue

## Preferred Languages

We prefer all communications to be in English.

## Policy

We follow the principle of [Coordinated Vulnerability Disclosure](https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure).

## Addressed Security Issues

- May 29, 2024: Removed exposed Google API Key from repository history
  - The API key `AIzaSyAS0BBI8nlRlGRoBAVnA6mn6RgpgDWveB4` was exposed in our repository history
  - The key has been **revoked** and removed from git history
  - Added firebase-config.js to .gitignore to prevent future leaks 