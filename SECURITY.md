# 🔐 Security Policy

We take the security of this project seriously. This document outlines how to responsibly report vulnerabilities and how we manage security-related issues.

---

## 🛡 Supported Versions

Security updates are provided only for active development branches:

| Version | Status |
|--------|--------|
| `main` | ✔ Supported |
| All others | ❌ Not actively maintained |

Please ensure you are testing against the latest version before reporting any issues.

---

## 🚨 Reporting a Vulnerability

If you discover a security issue, **please do not create a public GitHub issue**.

Instead, contact us privately via email:

📧 **security@example.com**

Include the following details to help us respond quickly:

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Screenshots or PoC if applicable
- Any suggested fixes

We aim to respond within **72 hours** and keep you updated throughout the process.

---

## 🔒 Responsible Disclosure

To protect users, we follow a standard responsible disclosure practice:

1. Vulnerability is reported privately  
2. We investigate and confirm the issue  
3. We develop a fix and prepare a security release  
4. We publish advisories **after** mitigation is available  

Credit will be given for responsible and helpful security reports, unless you request anonymity.

---

## 🧪 Security Best Practices for Contributors

To minimize risks when contributing:

- Do not commit secrets, API keys, or credentials  
- Avoid introducing unsafe dependencies  
- Validate and sanitize all user inputs  
- Follow secure coding guidelines for our stack (e.g., OWASP Top 10)
- Run tests and linters before submitting PRs  
- If unsure, ask in the Pull Request conversation

---

## ⚠️ Package and Dependency Security

We use automated vulnerability scanning where possible:

- GitHub Dependabot Alerts  
- npm audit / or equivalent tool in your stack  

Please respond promptly to flagged issues or dependency upgrade requests.

---

## 🔍 Known Security Issues

We track CVEs, advisories, and improvement needs through **GitHub Security Advisories**.

If you find something missing, report it privately as described above.

---

Thank you for helping keep this project and its users secure ❤️
