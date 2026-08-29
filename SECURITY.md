# Security Policy

## Supported versions

We release security updates for the **latest minor** of each public project.
Older minors receive best-effort fixes only.

## Reporting a vulnerability

Please **do not** file a public issue for security vulnerabilities.

Report privately by emailing **[security@m7xlab.top](mailto:security@m7xlab.top)**
with:

- A clear description of the issue and its impact
- Steps to reproduce or a proof-of-concept
- Affected versions / commits
- Your name and how you'd like to be credited (or "anonymous")

We acknowledge reports within **3 business days** and aim to publish a fix or
mitigation within **30 days**, depending on severity and complexity.

If a coordinated disclosure timeline is helpful for you (CVE, embargo, etc.),
let us know in your initial email.

## Scope

The following are in scope:

- Authentication / authorization bypasses
- Remote code execution
- SQL injection / SSRF / path traversal / XXE
- Sensitive data exposure (tokens, PII, secrets)
- Supply chain compromise of a released artifact

Out of scope: rate-limiting complaints, denial-of-service against our own
infrastructure, scanner output without a reproducible exploit.

## Recognition

We maintain a private thank-you list of reporters and are happy to credit you
publicly with your consent once a fix ships.
