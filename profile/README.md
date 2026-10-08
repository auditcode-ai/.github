# AuditCode

Code security research and verified audits. We find vulnerabilities that span multiple modules — the class per-file scanners routinely miss — using cross-module data-flow analysis, and reproduce every finding by hand before anyone is contacted.

**Track record:** 15 CVEs · 16 Linux kernel fixes backported to 92 stable branches. Full list with external links → [auditcode.ai/research](https://auditcode.ai/research)
**Kernel commits:** all mainline commits authored from @auditcode.ai → [git.kernel.org](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=auditcode)

**Audits:** we run the same engine on client codebases and deliver only confirmed vulnerabilities, with severity and fix guidance. Request an audit → contact@auditcode.ai

## Disclosure principles

- **Coordinated disclosure** · Reported privately first; 90-day default disclosure window.
- **Manual verification** · No AI-generated finding reaches a maintainer without human review.
- **Maintainer collaboration** · We credit maintainer security teams and provide diff-format patch suggestions where possible.
- **Minimum necessary detail** · Proof-of-concept shared privately; public advisories carry only what is needed to validate the fix.

Findings are fixed upstream through the Linux kernel CNA, GitHub Security Advisories and project maintainers. Published CVEs are indexed in the NVD. Full policy → [auditcode.ai/research#disclosure](https://auditcode.ai/research#disclosure)

## For maintainers

If you received a coordinated disclosure from `security@auditcode.ai`:
- Channel · security@auditcode.ai
- Methodology · [auditcode.ai/research/methodology](https://auditcode.ai/research/methodology)

AuditCode · Brussels, Belgium · [auditcode.ai](https://auditcode.ai)
