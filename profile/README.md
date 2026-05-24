# AuditCode Research

Coordinated security research on open-source software. We focus on
vulnerabilities that span multiple modules — the class per-file scanners
routinely miss — found through cross-module data-flow analysis and
reproduced by hand before any maintainer is contacted.

Findings are reported privately to maintainers under a coordinated embargo,
then published via GitHub Security Advisories and indexed in the National
Vulnerability Database.

→ [auditcode.ai/research](https://auditcode.ai/research)

## Disclosure principles

- **Coordinated disclosure** · Reported privately first; 90-day default
  disclosure window.
- **Manual verification** · No AI-generated finding reaches a maintainer
  without human review.
- **Maintainer collaboration** · We credit maintainer security teams and
  provide diff-format patch suggestions where the surrounding code permits.
- **Minimum necessary detail** · Proof-of-concept shared privately; public
  advisories carry only what is needed to validate the fix.

The full disclosure policy is documented at
[auditcode.ai/research#disclosure](https://auditcode.ai/research#disclosure).
If a maintainer is unresponsive, the matter may be referred to CERT/CC as a
neutral coordinator before publishing.

## Standards

Advisories are scored with CVSS v3.1 and classified against the CWE Top 25
and OWASP Top 10. Disclosure handling follows ISO/IEC 29147 and ISO/IEC 30111.

## For maintainers

If you received a coordinated disclosure from `security@auditcode.ai`:

- **Channel** · security@auditcode.ai
- **Disclosure policy** · [auditcode.ai/research#disclosure](https://auditcode.ai/research#disclosure)
- **Methodology** · [auditcode.ai/research/methodology](https://auditcode.ai/research/methodology)

## Advisories

Advisories are published at [auditcode.ai/research](https://auditcode.ai/research)
and recorded on the affected projects' GHSA pages.

---

AuditCode Research · Brussels, Belgium · [auditcode.ai](https://auditcode.ai)
