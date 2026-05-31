# Security-Code-Review-Portfolio

> Documented vulnerability findings from real-world labs and intentionally vulnerable applications.

## About

This portfolio documents my hands-on security code review work across multiple platforms and vulnerability classes. Each finding includes the vulnerable code snippet, an explanation of the flaw, how it can be exploited, and the recommended fix, mapped to the OWASP Top 10 where applicable.

## Repository Structure

```
/findings
  /os-command-injection
  /sql-injection
  /xss
  /authentication-flaws
  /[vulnerability-type]
```

Each folder contains a `README.md` with:
- Vulnerability overview
- Vulnerable code snippet
- Exploitation walkthrough
- Recommended fix
- OWASP / CWE mapping

---

## Sources

Findings are sourced from:
- **Secure Code Dojo - OWASP**
- **OverTheWire** - wargame labs with visible vulnerable code
- **PortSwigger Web Security Academy** - code review focused labs
- **DVWA** (Damn Vulnerable Web Application)
- **WebGoat** - OWASP's deliberately vulnerable app
- **YesWeHack GitHub** - vulnerable code snippet examples
- **GitHub Advisory Database** - real-world CVEs with code-level analysis

---

## Vulnerability Classes Covered

- [ ] OS Command Injection
- [ ] SQL Injection
- [ ] Cross-Site Scripting (XSS)
- [ ] Broken Authentication
- [ ] Insecure Deserialization
- [ ] Security Misconfiguration
- [ ] *(expanding)*

---
