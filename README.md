# PortSwigger Web Security Labs Writeups

This repository contains structured writeups from completing the **PortSwigger Web Security Academy**, focused on understanding real-world web application vulnerabilities and their remediation.

---

## Focus

- Web application exploitation techniques
- Root cause analysis of vulnerabilities
- Secure design and mitigation strategies

---

## Topics

_(The repository structure reflects full coverage of PortSwigger topics, with additional writeups added as they are completed.)_

### SQL Injection

- [Data Exfiltration](sqli/data-exfiltration/)
- [Login Bypass](sqli/login-bypass/)

---

### Server-Side Request Forgery (SSRF)

- [Localhost Access](ssrf/localhost-access/)
- [IP Enumeration](ssrf/ip-enumeration/)

---

### File Upload

- [RCE - Unrestricted File Type](file-upload/rce-unrestricted-file-type/)
- [RCE - Content-Type Bypass](file-upload/rce-content-type-bypass/)

---

### OS Command Injection

- [Command Execution](os-command-injection/command-execution/)

---

### Path Traversal

- [Arbitrary File Read](path-traversal/arbitrary-file-read/)

---

### Authentication

- [Username & Password Enumeration](authentication/username-password-enumeration/)
- [Bypassing 2FA](authentication/bypass-2fa/)

---

### Access Control

- [Horizontal Privilege Escalation](access-control/horizontal-privilege-escalation/)
- [Horizontal → Vertical Privilege Escalation](access-control/horizontal-to-vertical-privilege-escalation/)

---

## Approach

This repository emphasises depth over repetition.

Core concepts are explained thoroughly when first encountered. Subsequent labs build on these foundations rather than repeating basic explanations, allowing writeups to remain concise and focused on exploitation logic, root cause, and impact.

This reflects real-world security work, where understanding patterns and behaviours is more valuable than repeating definitions.

Each lab writeup follows a consistent structure:

- **Vulnerability identification**
- **Exploitation methodology**
- **Impact analysis**
- **Root cause explanation**
- **Mitigation and secure design principles**
- **Key learning**

Additional elements included where relevant:

- **Post-exploitation exploration**
- **Observations of implemented security controls**

---

## Key Skills Demonstrated

- Exploitation of common web vulnerabilities
- Root cause analysis and vulnerability reasoning
- Understanding of secure coding principles and vulnerability mitigation approaches

---

All activities were performed in authorised lab environments.
