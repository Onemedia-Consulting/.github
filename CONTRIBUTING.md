# Contributing to Onemedia Consulting projects

This is the org-default contributing guide. Individual repositories may provide their own `CONTRIBUTING.md` that supersedes this one.

## Where the conventions live

OMC's engineering practice — branching, commits, style, security, AI engineering — is codified in the **engineering handbook** at [`Onemedia-Consulting/engineering-handbook`](https://github.com/Onemedia-Consulting/engineering-handbook) (private; access available to OMC employees and contractors).

This file is a pointer, not a duplicate. Read the relevant handbook section before contributing.

## Quick reference

- **Branches:** `<type>/<name>` where `<type>` is one of `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `wip`. See [branching-strategy.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/branching-strategy.md).
- **Commits:** [Conventional Commits](https://www.conventionalcommits.org/), signed (GPG or SSH). See [commit-guidelines.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/commit-guidelines.md).
- **Code style:** Python via `ruff` + `mypy`; line length 100. See [styleguide.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/styleguide.md).
- **Security:** see [secure-coding-guidelines.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/secure-coding-guidelines.md) and [security-policy.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/security-policy.md). Vulnerability reports → [SECURITY.md](./SECURITY.md).
- **AI / LLM work:** see [ai-engineering-guidelines.md](https://github.com/Onemedia-Consulting/engineering-handbook/blob/main/ai-engineering-guidelines.md) — mandatory for any repo using LLMs, MCP, or agent harnesses.

## Pull requests

- Use the org-default PR template (auto-populated). Customize for the repo if a project-specific template is provided.
- Link the issue your PR addresses (`Closes #N`).
- Required status checks must pass.
- Reviewer approval required before merge.

## Reporting bugs and proposing features

Use the org-default issue templates (Bug report, Feature, Task). Repos with project-specific templates override these.

## Questions

For OMC contributors: ask in the relevant Slack/Linear channel. For external contributors: open an issue with the question label.
