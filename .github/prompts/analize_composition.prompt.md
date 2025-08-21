---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Analyze components and libraries"
---
## 3. COMPONENTS & LIBRARIES ANALYSIS

### Security Components
- Identify authentication libraries and implementation details
- Document authorization components and access control libraries
- Analyze encryption/cryptography implementations
- Review input validation and output encoding libraries

### Database Components
- Identify ORMs, query builders, and database drivers
- Analyze how SQL queries are constructed and executed
- Review parameterization practices and injection prevention
- Examine data access patterns for security issues

### Frontend Components
- Analyze JavaScript frameworks and their security implications
- Review client-side validation and security controls
- Examine DOM manipulation and XSS prevention mechanisms
- Evaluate frontend/backend trust boundaries

### API & Integration Components
- Identify API clients and third-party service SDKs
- Review API security controls (authentication, rate limiting, etc.)
- Analyze how API keys and secrets are managed
- Evaluate input validation for external data sources

## Deliverable Format
Markdown report including:
1. Executive summary
2. Detailed findings per section
3. Code references (file paths and line numbers)
4. Risk severity ratings
5. Remediation recommendations
6. Technical debt implications
7. Security improvement roadmap

## Reference standards:
- OWASP FIASSE with SSEM attributes
- OWASP Secure Coding Practices
- Cloud Native Security Best Practices
- Framework-specific security guidelines

Expected output format: Markdown report with clear sections, code references (file and line), and actionable recommendations.