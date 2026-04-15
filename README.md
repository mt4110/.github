# mt4110/.github

## Purpose

This repository is the shared home for human-facing defaults across repositories under `mt4110`.

It is intentionally small. It holds reusable community health files that GitHub can fall back to when a repository does not define its own local version.

Included here:

- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `SUPPORT.md`
- `pull_request_template.md`
- `profile/README.md`

## What Stays Out

These concerns do not belong in the shared defaults repository:

- workflows
- release scripts
- package-specific `RELEASING.md`
- issue forms tied to one package
- Dependabot configuration
- branch protection
- Actions permissions
- Discussions enablement
- npm publish settings

Those stay repo-local or in GitHub and npm settings.

## Local Overrides

Any repository may keep its own local version of these files when sharper repo-specific wording is more useful.

That is expected, not a failure of the shared default.
