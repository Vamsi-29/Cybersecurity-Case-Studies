# Cybersecurity Case Studies

A collection of practical, research-based cybersecurity case studies covering real-world vulnerabilities, attack paths, root causes, detection, and remediation.

> **Portfolio note:** These are research and analysis writeups unless explicitly identified as work personally performed or discovered by me. They are not claims of original vulnerability discovery.

## Case Studies

| Category | Case Study | Focus |
|---|---|---|
| Web Security | [Apache Tomcat CVE-2026-76183](web/apache-tomcat-cve-2026-76183.md) | WebSocket authorization bypass caused by incorrect request-path parsing |
| Web Security | [React2Shell — CVE-2025-55182](web/react2shell-cve-2025-55182.md) | Unsafe deserialization in React Server Components leading to pre-authentication RCE |
| Web Security | [RabbitMQ CVE-2026-67237](web/rabbitmq-cve-2026-67237-oauth-bootstrap-xss.md) | Reflected XSS in OAuth bootstrap JavaScript due to unescaped token data |
| Incident Response | [Okta Support-System Breach (2023)](incident-response/okta-support-system-breach-2023.md) | Support-data exposure, session-token handling, and incident response |
| DevSecOps | [Git Push Pipeline Metadata Injection — CVE-2026-3854](devsecops/github-git-push-pipeline-cve-2026-3854.md) | Delimiter injection in internal metadata leading to server-side command execution |
| Authentication | [Cisco License On-Prem CVE-2026-20328](authentication/cisco-license-on-prem-cve-2026-20328-password-reset.md) | Unauthenticated arbitrary-account password reset in management interface |
| Network Security | [Node.js CVE-2026-105482](network-security/nodejs-cve-2026-105482-dns-nul-truncation.md) | NUL-byte hostname truncation in c-ares-backed DNS resolution and allowlist mismatch |

## Approach

Each case study focuses on:
- Attack surface and trust boundaries
- Technical root cause
- Exploitation/attack path at an appropriate, safe level of detail
- Security impact
- Detection opportunities
- Remediation
- Practical lessons for penetration testing and defensive engineering

## Research Integrity

These case studies are intended to demonstrate security analysis and technical communication, not original vulnerability discovery. For each case study, source claims to vendor advisories, vulnerability databases, and public reporting where applicable. Readers should treat the cited primary sources as authoritative for affected versions, severity, disclosure details, and remediation guidance.

When a case study discusses exploitation or testing, the examples are presented as controlled-analysis scenarios unless the writeup explicitly states otherwise. No claim of personal discovery, reporting, or exploitation should be inferred from inclusion in this repository.
