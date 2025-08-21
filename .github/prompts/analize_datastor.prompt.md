---
mode: "agent"
tools: ['codebase', 'extensions', 'search', 'searchResults', 'usages', 'context7']
description: "Generate a data and output security report"
---

## 4. DATASTORES & TEMPLATING ANALYSIS
perform security analysis of the codebase

### Datastores
- Document all databases, caches, and storage mechanisms
- Review database security configurations
- Analyze connection security and credential management
- Identify backup and recovery mechanisms

### Database Schema
- Analyze table structures and relationships
- Review schema security controls (constraints, triggers)
- Identify sensitive data storage patterns
- Evaluate data integrity controls

### Data Access Patterns
- Document how the application queries data
- Review transaction handling security
- Analyze privilege management for data access
- Identify potential for data leakage

### Templating Engines
- Identify template engines and rendering mechanisms
- Review how user data is incorporated into templates
- Analyze output encoding and XSS prevention
- Evaluate template inclusion security

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