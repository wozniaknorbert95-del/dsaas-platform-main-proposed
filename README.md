# dsaas-platform-main — DSaaS platform (proposed changes)

This repository (proposed branch) contains suggested documentation and governance changes to make the platform's purpose and mapping to tenants explicit for external reviewers.

## Elevator pitch (for reviewers)

DSaaS is a multi-tenant operating platform for autonomous company systems (Company Brains). This proposal clarifies how the canonical platform (policies, ledgers, ontologies) relates to tenant instances like QuietForge, and adds minimal security automation and responsible disclosure guidance.

## Summary of proposed changes

- Add a short English README describing platform vs tenant responsibilities and technical taste.
- Add SECURITY.md (responsible disclosure: contact via quietforge site).
- Add a simple Gitleaks workflow to detect accidental secret commits.
- Propose CODEOWNERS for docs/ to require review on policy changes.

## Quick verification (local)

```bash
# basic checks
# run linters / typecheck if available
npm ci || true
npm run typecheck || true
```

## Owner

Owner: Norbert Wozniak — DSaaS Platform
