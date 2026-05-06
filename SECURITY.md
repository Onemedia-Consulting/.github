# Security Policy

## Reporting a vulnerability

If you have discovered a security issue in any Onemedia Consulting (OMC) repository, please report it to us privately rather than opening a public issue or pull request.

**Email:** `security@onemedia-consulting.com`

When reporting, include:

- The repository and version (commit SHA or tag) where the issue was observed.
- A clear description of the issue and its potential impact.
- Reproduction steps or a proof of concept where possible.
- Your name or handle for credit (optional).

## Response SLAs

We aim to acknowledge new reports within **2 business days** and provide a substantive update within **5 business days**. Resolution timelines vary by severity:

| Severity | Resolution target |
|---|---|
| Critical (active exploitation, data exposure) | 7 days |
| High (broken access controls, no active exploitation) | 30 days |
| Medium | 90 days |
| Low | best-effort, next regular cycle |

"Resolution" means a deployed patch or, where deployment is not yet possible, a documented mitigation in the affected repository.

## Scope

This policy applies to all repositories owned by the `Onemedia-Consulting` GitHub organisation. For repositories that consume third-party services (e.g., Adobe Marketo MCP), report any vulnerability in the third-party component to that vendor's disclosure channel as well.

## Out of scope

- Findings derived solely from automated scanners without a working proof of concept.
- Issues in third-party dependencies that are already publicly disclosed and being tracked via Dependabot.
- Reports targeting OMC's customer-facing websites or marketing infrastructure (those have their own contact paths).

## Disclosure timing

We follow a coordinated disclosure model. After a fix is in place we may publish an advisory on the affected repository. We credit reporters who request it. Please do not disclose publicly before a fix is released or 90 days have elapsed since first acknowledgement, whichever is sooner.

## Internal practice

OMC engineers follow the [Security Policy](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/security-policy.md) and [Secure Coding Guidelines](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/secure-coding-guidelines.md) in the engineering handbook (private; access available to OMC employees and contractors).
