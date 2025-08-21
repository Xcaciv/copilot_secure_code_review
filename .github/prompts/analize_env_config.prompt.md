---
mode: "agent"
tools: ['codebase', 'extensions', 'search', 'searchResults', 'usages', 'context7']
description: "Generate an analysis of configuration and environment settings"
---
## 5. CONFIGURATION & ENVIRONMENT ANALYSIS

### Configuration Files
- Identify all configuration files and their purposes
- Flag hardcoded secrets, credentials, or sensitive values
- Review environment-specific configurations
- Analyze security-critical configuration options

### Environment Variables
- Document environment variables used by the application
- Review how environment variables are loaded and used
- Identify sensitive data in environment variables
- Analyze default fallback values for security implications

### Infrastructure Configuration
- Review web server, container, and infrastructure configurations
- Analyze network security controls
- Identify resource access controls
- Examine logging and monitoring configuration

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