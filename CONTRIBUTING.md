# Contributing

Thanks for considering a contribution.

This is account-wide fallback guidance. Start with the target repository's README and any local contribution files;
repository-specific policy always wins. A repository may be archived, experimental, personal, or no longer accepting
changes even when its source remains public.

## Before starting

- Confirm that the repository is active and that the proposed change fits its current scope.
- Check open Issues and pull requests for an existing discussion or implementation.
- Use the repository's own setup, branch, build, test, formatting, and compatibility instructions where they exist.
- Follow any local issue-first rule. When none exists, choose the smallest useful discussion route for the change; a
  large behavioral or architectural proposal may benefit from an Issue, but this fallback does not require one.
- Do not assume a maintainer can provide product support, implementation coaching, or a response within a particular
  time.

## Make the change reviewable

Keep the contribution focused and explain both **what changed** and **why**. Include the validation that is proportionate
to the change: tests, build commands, manual checks, screenshots, fixtures, or an exact reason a check was not available.

A contributor should be able to explain and maintain the submitted work. When that is not fully true, state the exact
limitation rather than hiding it behind a green command or polished diff.

Do not include:

- credentials, tokens, cookies, private keys, or environment secrets;
- private logs, personal data, or unrelated account information;
- generated or third-party material you do not have the right to submit; or
- broad formatting, dependency, or refactoring changes unrelated to the contribution.

By submitting material, you confirm that you have the right to contribute it and understand that the target repository's
own license and contribution policy govern the accepted result. No account-wide CLA, DCO signoff, support promise, or
issue-first rule is invented by this fallback document.

## Generative-AI assistance

Substantial generative-AI assistance is welcome when it is disclosed honestly and the result receives real human
judgment.

In the pull request's **Contribution context** section, describe:

- the tool or workflow when materially relevant;
- which areas were substantially generated or shaped with it;
- what you personally reviewed, tested, or verified; and
- any part you cannot confidently explain or maintain.

Routine autocomplete, spelling help, or minor wording suggestions do not need an inventory. The purpose is not to punish
AI-assisted work or estimate a percentage. It gives maintainers the context needed to review behavior, security,
maintainability, and future ownership honestly.

Concrete concerns should be discussed as concrete concerns: missing explanation, missing tests, excessive change size,
generated artifacts, or maintainability risk. Do not treat a contributor's tool choice as a substitute for reviewing the
actual change.

## Pull requests

Use the provided pull-request template where GitHub offers it. Keep the description current as the contribution changes,
answer review questions directly, and avoid resolving conversations whose concern is not actually addressed.

A maintainer may ask for a smaller change, more explanation, additional validation, or another approach. Acceptance,
priority, release timing, and continued maintenance remain repository-owner decisions.

## Security and sensitive reports

Do not publish credentials, exploit details, or other sensitive material merely because no global `SECURITY.md` exists.
Use the target repository's private reporting route when it provides one. When no private route is named, disclose no
sensitive details publicly: use an available non-sensitive contact surface only to request a private route, or retain the
report until one exists.
