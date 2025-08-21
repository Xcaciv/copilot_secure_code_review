---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Generate routes summary"
---

# Language & Framework Security Analysis Request

## Objective
Perform a comprehensive security analysis of the codebase focusing on language, framework, architecture, and deployment aspects.

## Required Input
1. Source code repository or files
2. Industry-specific compliance requirements (e.g., HIPAA, PCI-DSS, GDPR)
3. Applicable security standards (e.g., OWASP Top 10, CWE)
4. Current deployment environment details
5. Build pipeline configuration files

## Analysis Scope

### Programming Language Assessment
- Primary language(s) identification and version analysis
- Language-specific vulnerability scanning
- Static code analysis for:
  * Unsafe function usage
  * Deprecated features
  * Memory management issues
  * Input validation patterns
  * Error handling practices

### Framework Evaluation
- Framework identification and version verification
- Security feature implementation review
- CVE and security advisory compliance check
- Configuration assessment against framework security guidelines

### Architectural Review
- System architecture pattern documentation
- Component boundary analysis
- Authentication/Authorization flow review
- Data flow security evaluation
- Third-party integration security assessment

### DevOps Security
- CI/CD pipeline security control audit
- Infrastructure-as-Code security review
- Container security analysis
- Environment configuration evaluation

## Deliverable Format
Markdown report including:
1. Executive summary
2. Detailed findings per section
3. Code references (file paths and line numbers)
4. Risk severity ratings
5. Remediation recommendations
6. Technical debt implications
7. Security improvement roadmap

Reference standards:
- OWASP FIASSE with SSEM attributes
- OWASP Secure Coding Practices
- SANS CWE Top 25
- Cloud Native Security Best Practices
- Framework-specific security guidelines