# Contributing to PrightCord

PrightCord repositories use different languages, build systems, and release workflows. Treat the target repository as the source of truth for setup, architecture, testing, and release instructions.

## Before you change anything

- Read the repository's `README.md` and any repo-local `CONTRIBUTING.md`, `AGENTS.md`, or development docs.
- Search existing issues and pull requests before opening duplicate work.
- Keep the change focused. Avoid unrelated cleanup or refactors.

## Implementation

- Preserve existing public behavior unless the change intentionally modifies it.
- Add regression coverage for bug fixes when the repository has an applicable test surface.
- Add or update tests for new behavior at the narrowest useful level.
- Update documentation when user-visible behavior, interfaces, configuration, or durable workflows change.
- Never commit credentials, tokens, private keys, production data, or other secrets.

## Verification

Run the checks documented by the target repository. In the pull request, list the exact commands or manual checks you ran and note anything you could not verify.

## Pull requests

A useful pull request should explain:

- the problem or goal;
- the change made;
- how it was verified;
- any compatibility, migration, or follow-up work;
- related issues or discussions, when applicable.
