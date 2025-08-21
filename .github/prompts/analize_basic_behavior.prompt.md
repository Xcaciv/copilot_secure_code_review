---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Analysis of business level"
---
# 1. APPLICATION BEHAVIOR ANALYSIS

## Objective
Perform a comprehensive security analysis of the codebase focusing on the business purpose and audience. Then look at the roles involved with an eye to access control. From a high level perspective analyze how data is handled and the types of data involved.

### Business Purpose
- Identify the application's primary function and business objectives
- Determine critical business workflows and processes
- Identify security-sensitive operations
- Note regulatory compliance requirements (PCI, HIPAA, GDPR, etc.)

### Target Audience
- Determine if the application is for internal users, external customers, or both
- Identify the expected user base size and types of users
- Assess implications of the user base on security posture

### Data Handling
- Identify ALL types of data the application stores, processes, or transmits
- Explicitly flag sensitive data (PII, financial, healthcare, etc.)
- Document data flows between components and external systems
- Note data retention policies if present

### User Roles & Access Control
- Map the complete role hierarchy and permission structure
- Identify privilege escalation paths
- Analyze role separation enforcement mechanisms
- Document how access control decisions are made and enforced

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