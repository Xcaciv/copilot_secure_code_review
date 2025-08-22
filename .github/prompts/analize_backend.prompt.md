---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Generate backend analysis summary"
---
## 7. API & ENDPOINT ANALYSIS

### HTTP Routes & Endpoints
- Map all API endpoints and their functionality
- Document HTTP methods, parameters, and responses
- Identify unauthenticated or public endpoints
- Analyze parameter validation and sanitization
- Review rate limiting and anti-automation controls

### API Security Controls
- Evaluate API authentication mechanisms
- Review authorization for API endpoints
- Identify CSRF protections
- Analyze input validation comprehensiveness

## Deliverable Format
Markdown report including:
1. Executive summary
2. Detailed findings per section
3. Code references (file paths and line numbers)
4. Remediation recommendations

## Reference standards:
- OWASP FIASSE with SSEM attributes
- OWASP Secure Coding Practices
- Cloud Native Security Best Practices
- Framework-specific security guidelines

Expected output format: Markdown report with clear sections, code references (file and line), and actionable recommendations.