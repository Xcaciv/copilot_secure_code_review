---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Generate risk summary"
---
## 8. RISK ANALYSIS & SECURITY RECOMMENDATIONS

### Vulnerability Assessment
- Identify high-risk code patterns and potential vulnerabilities
- Map findings to OWASP Top 10 or other relevant frameworks
- Assess impact and exploitability of identified issues

### Security Control Evaluation
- Analyze effectiveness of implemented security controls
- Identify missing or inadequate security measures
- Review defense-in-depth strategy

### Third-Party Risk Assessment
- Evaluate security implications of dependencies
- Identify outdated or vulnerable components
- Review trust relationships with external services

### Security Recommendations
- Provide prioritized security improvement recommendations
- Suggest specific mitigations for identified issues
- Recommend additional security controls where appropriate

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