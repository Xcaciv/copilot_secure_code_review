---
mode: "agent"
tools: ['codebase', 'extensions', 'search', 'searchResults', 'usages', 'context7']
description: "Generate a detailed analysis of authentication and authorization"
---
## 6. AUTHENTICATION & AUTHORIZATION ANALYSIS

### Authentication Methods
- Document all authentication mechanisms
- Analyze credential storage and transmission
- Review MFA implementation if present
- Evaluate session management security
- Identify account recovery mechanisms and their security

### Authorization Controls
- Map the authorization flow and decision points
- Analyze how permissions are enforced throughout the application
- Review authorization checks in critical functions
- Identify potential privilege escalation vectors
- Document access control bypass opportunities

### Security Decorators & Middleware
- Identify security-related decorators and interceptors
- Review how they're applied across the application
- Analyze consistency of security control application
- Evaluate how security controls can be bypassed

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