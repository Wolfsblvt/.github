# Wolfsblvt GitHub defaults

[![Community files: fallback](https://img.shields.io/badge/community_files-fallback-4B69C6)](#what-github-inherits)
[![Local policy: wins](https://img.shields.io/badge/local_policy-wins-2D7D76)](#start-with-the-project)
[![Funding: optional](https://img.shields.io/badge/funding-optional-8C6BB1)](#funding-without-promises)

**A shared starting point, not a one-size-fits-all policy.**

Contribution guidance, a focused pull-request template, and an optional funding destination for
[@Wolfsblvt's public repositories](https://github.com/Wolfsblvt?tab=repositories).
This repository keeps those account-wide fallbacks in one place; each project's own rules come first.

A fallback file is not a sign that a project is active, accepting contributions, or offering support.

**[Read the contribution guide](CONTRIBUTING.md)** · [See the defaults](#what-github-inherits) · [Maintain them](#maintaining-the-defaults)

## Start with the project

**Contributing?** Begin with the target repository's README and local contribution guidance. Confirm that the
project accepts changes, check existing issues and pull requests, and follow its own setup and validation instructions.
When no local guide exists, [CONTRIBUTING.md](CONTRIBUTING.md) supplies the baseline. A useful pull request explains
what changed, why, how it was checked, and any relevant assistance or limitations.

**Maintaining a repository?** Leave a supported community file absent to use the account default, or add a local file
of the same type when the project needs its own contract. There is nothing to install or copy: GitHub presents the
fallback where it applies. Verify the contribution screen or template in the receiving repository, not just this
repository's file list.

## What GitHub inherits

| File | What it supplies | Inheritance |
| --- | --- | --- |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution scope, reviewable changes, validation, and assistance disclosure | Fallback when no local guide exists |
| [Pull-request template](.github/pull_request_template.md) | What changed, why, validation, and contribution context | Fallback when no local template exists |
| [FUNDING.yml](FUNDING.yml) | Wolf's optional Ko-fi destination | Fallback when no local override exists; Sponsor display is controlled per repository |
| [FUNDING.md](FUNDING.md) | Optional-support scope and product-specific offer boundaries | Explanatory guide; not inherited by GitHub |
| [README.md](README.md) | This repository's scope, maintenance, and rights | Not inherited |

GitHub's [default community-file mechanism](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
selects the matching fallback without copying it into downstream repositories, Git history, clones, packages, or
downloads. A repository-local file overrides the matching default.

Local policies can therefore carry exact build commands, branch rules, support routes, and contribution expectations
without turning this fallback into a rulebook for every project.

## Funding without promises

[FUNDING.yml](FUNDING.yml) names an available funding destination. It does **not** enable Sponsorships across the
account: each repository decides whether to display its
[Sponsor button](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/displaying-a-sponsor-button-in-your-repository)
through its own settings.

Inheriting that destination does not reactivate an archived project. Optional support alone creates no service tier,
priority, private access, support obligation, or special treatment. Only a benefit explicitly offered by an active
published tier creates that stated benefit; it does not create an unstated support or access commitment.

[Funding details](FUNDING.md) explain the distinction. A project's own license, paid/free scope, maintenance status,
and accepted contribution policy remain authoritative. This account-wide fallback adopts no universal open-source
completeness promise and no additional contributor-rights agreement.

## What stays with each project

These defaults deliberately do not provide:

- **Community and contact policies:** issue forms or labels, Discussion forms, privacy, security reporting, support,
  a code of conduct, or governance.
- **Automation and repository controls:** workflows, Dependabot configuration, branch rules, or repository settings.
- **Project licenses:** every downstream public repository still needs its own explicit, product-appropriate license.
  Nothing here supplies or implies one.

Those surfaces need product-specific facts, a real receiver, or a deliberately selected common contract.
Repository-specific policy belongs with the repository that owns it.

## Maintaining the defaults

**An inherited-file change can affect many repositories immediately.** Keep the defaults small and broadly truthful:

1. Inspect the public repositories that would inherit the changed file, including active and archived receivers.
2. Preserve useful local overrides.
3. Avoid promises whose receiver or capacity does not exist.
4. After publication, verify one inheriting repository and one local-override control.
5. Remove or narrow a default when it stops being honest.

The initial publication was reviewed across Wolf's public repositories on 2026-08-20. That baseline does not replace
the same file-by-file check for future additions.

## License

Copyright © 2026 Wolfsblvt.

Except for the limited rights necessary for GitHub to host, display, and apply these files as account-default community
files for repositories owned by Wolfsblvt, no license is granted. This material is not offered for reuse, copying,
modification, redistribution, sublicensing, or incorporation into other projects.

Each downstream repository remains governed by its own license. All rights reserved.
