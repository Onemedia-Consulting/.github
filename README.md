# Onemedia-Consulting / .github

Default community-health files for the **Onemedia Consulting** GitHub organisation. Files in this repository auto-apply to every OMC repository that does not provide its own version.

## What's here

- [`CONTRIBUTING.md`](./CONTRIBUTING.md) — points to the engineering handbook
- [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) — Contributor Covenant 2.1
- [`SECURITY.md`](./SECURITY.md) — vulnerability disclosure
- [`.github/pull_request_template.md`](./.github/pull_request_template.md) — default PR template
- [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE) — bug, feature, and task issue forms

## How GitHub uses this

When a repo in `Onemedia-Consulting` does not contain its own version of one of these files, GitHub uses the version here. Per-repo files always override these defaults — repos can opt out of any specific template by providing their own.

## How OMC uses this

The intent is consistency across all OMC repositories without per-repo copy-paste. New repos start with sensible templates the moment they are created. Existing OMC repos (`OMC_SSFS`, `data-cleaner`, `Marketo-API`, `poc-marketo-agent`) gain these defaults passively — no code change required.

## Related

- [`Onemedia-Consulting/engineering-handbook`](https://github.com/Onemedia-Consulting/engineering-handbook) (private) — prose conventions: branching, commits, style, security, AI engineering. Referenced from each repo's `CLAUDE.md`.

## Visibility note

This repository is public **only because GitHub requires the org-default `.github` repository to be public for community-health files to propagate**. The handbook with engineering conventions remains private. Nothing sensitive is committed here.
