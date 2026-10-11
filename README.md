# Cybersecurity Case Studies

A collection of practical, research-based cybersecurity case studies covering real-world vulnerabilities, attack paths, root causes, detection, and remediation.

> **Portfolio note:** These are research and analysis writeups unless explicitly identified as work personally performed or discovered by me. They are not claims of original vulnerability discovery.

## Case Studies

| Category | Case Study | Focus |
|---|---|---|
| Web Security | [Apache Tomcat CVE-2026-76183](web/apache-tomcat-cve-2026-76183.md) | WebSocket authorization bypass caused by incorrect request-path parsing |
| Web Security | [React2Shell — CVE-2025-55182](web/react2shell-cve-2025-55182.md) | Unsafe deserialization in React Server Components leading to pre-authentication RCE |
| Incident Response | [Okta Support-System Breach (2023)](incident-response/okta-support-system-breach-2023.md) | Support-data exposure, session-token handling, and incident response |

## Approach

Each case study focuses on:
- Attack surface and trust boundaries
- Technical root cause
- Exploitation/attack path at an appropriate, safe level of detail
- Security impact
- Detection opportunities
- Remediation
- Practical lessons for penetration testing and defensive engineering
