# Contributing to UMA-RLM

Thank you for your interest in contributing to UMA-RLM.

## Contributor License Agreement

Before we can accept any contribution you must sign the
UMA-RLM Contributor License Agreement (CLA). This is a
one-time step that covers all your future contributions
to this project.

When you open a pull request the CLA Assistant bot will
check your status and post instructions if you have not
yet signed. To sign, post the following comment on your PR:

> I have read the CLA Document and I hereby sign the CLA

You can read the full agreement here: [CLA.md](CLA.md)

This is required for all contributions including
documentation fixes.

## Commit signing

All commits must be GPG or SSH signed.
GitHub will display a Verified badge on signed commits.
Setup guide:
https://docs.github.com/en/authentication/managing-commit-signature-verification

## Development setup

See the Quickstart section in [README.md](README.md).

## PR expectations

See [AGENTS.md](AGENTS.md) §9 for the full patch expectations,
definition of done, and code style rules.

## Security-sensitive paths

Changes to the following paths receive extra scrutiny and
may take longer to review:

- `uma/retrieve/`
- `uma/memory/`
- `uma/common/`
- `uma/runtime/`
- `uma/common/injection_patterns.yaml`
- `.github/`
