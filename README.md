# Wolfsblvt GitHub defaults

This repository provides a small set of default community files for public repositories owned by
[`@Wolfsblvt`](https://github.com/Wolfsblvt).

GitHub uses a default file only when the target repository does not contain its own file of the same type. A local
repository policy always wins. The defaults are fallback contracts, not a promise that every historical repository is
active, accepting contributions, supported, or maintained on the same schedule.

## Files in this repository

| File | Purpose | GitHub inheritance |
| --- | --- | --- |
| [`README.md`](README.md) | explains this repository's scope, effects, maintenance contract, and license boundary | not inherited |
| [`FUNDING.yml`](FUNDING.yml) | supplies Wolf's optional Ko-fi destination to repositories that choose to display GitHub's Sponsor button | inherited when no local override exists |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | gives contributors a small honest baseline when a repository has no product-specific contribution guide | inherited when no local override exists |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | asks for the change, reason, validation, and relevant contribution context without inventing repository-specific commands or gates | inherited when no local override exists |

## Inheritance and overrides

The community files and pull-request template identified above are exposed through GitHub's default community-health
mechanism. They are not copied into downstream repositories or their clones. `README.md` applies only to this repository
and is never an account-default file.

A repository-local file overrides the matching default. This is deliberate: a mature product may need exact build
commands, branch rules, support routes, security policy, or contribution expectations that do not belong in an
account-wide fallback.

The initial publication decision was reviewed against every public repository owned by Wolf on 2026-08-20, including
active and archived receivers. Future additions still require the same file-by-file check; placing a new inheritable
file here may publish it across many repositories immediately.

## Funding behavior

`FUNDING.yml` defines an available funding destination. It does **not** enable GitHub Sponsorships on every repository.
Each repository separately decides whether to display the Sponsor button through its own feature settings. Archived
repositories may inherit the destination without becoming active or supported again.

Optional support creates no service tier, priority, access, support obligation, or special treatment.

## Deliberately not global

This repository currently does not provide default:

- Issue forms or labels;
- privacy policy;
- security-reporting policy;
- support policy;
- code of conduct;
- governance document;
- Discussion forms;
- workflows, Dependabot configuration, branch rules, or repository settings; or
- downstream repository licenses.

Those surfaces need product-specific facts, a real receiver, or a deliberately selected common contract. A file does not
become useful merely because GitHub has an empty drawer for it.

Every downstream public repository still needs its own explicit product-appropriate license. Nothing in this account-
default repository supplies or implies one.

## Maintenance

Keep these defaults small and broadly truthful. Before changing one:

1. inspect the public repositories that would inherit it;
2. preserve useful local overrides;
3. avoid promises whose receiver or capacity does not exist;
4. verify one inheriting repository and one local-override control after publication; and
5. remove or narrow a default when it stops being honest.

Repository-specific contribution and community policy belongs with the repository that owns it.

## License

Copyright © 2026 Wolfsblvt.

Except for the limited rights necessary for GitHub to host, display, and apply these files as account-default community
files for repositories owned by Wolfsblvt, no license is granted. This material is not offered for reuse, copying,
modification, redistribution, sublicensing, or incorporation into other projects.

Each downstream repository remains governed by its own license. All rights reserved.
