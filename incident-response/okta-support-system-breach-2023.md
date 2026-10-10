# Okta Support-System Breach (2023)

> Research-based incident case study; not a claim of personal discovery.

## Overview

In October 2023, an attacker accessed files in Okta's customer support case-management system using a compromised service-account credential. Some customer-uploaded HTTP Archive (HAR) files contained session tokens. Okta reported that files associated with 134 customers were accessed and that tokens from those files were used to hijack sessions at five customer organizations. A later update described additional exposure of support-system users' names and email addresses.

## Security Lessons

- Treat HAR files as sensitive because they can contain cookies, authorization headers, and session tokens.
- Store service-account credentials in managed secrets infrastructure rather than personal browser profiles.
- Apply least privilege and monitor support-system access to customer attachments.
- Revoke exposed sessions quickly and investigate identity events for suspicious administrative activity.
- Use phishing-resistant MFA, session-context controls, and reliable audit logs for privileged identities.

## References

1. Okta root-cause analysis: https://sec.okta.com/articles/2023/11/unauthorized-access-oktas-support-case-management-system-root-cause/
2. Okta initial disclosure: https://sec.okta.com/articles/2023/10/tracking-unauthorized-access-oktas-support-system/
3. Okta November update: https://sec.okta.com/articles/october-security-incident-recommended-actions/
4. BeyondTrust incident report: https://www.beyondtrust.com/blog/entry/okta-support-unit-breach
5. Cloudflare incident report: https://blog.cloudflare.com/how-cloudflare-mitigated-yet-another-okta-compromise/
