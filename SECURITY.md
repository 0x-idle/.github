# Security Policy

0xidle contains experimental software built mostly in spare time.

We still care about security.

We just don't want experimental status to be mistaken for enterprise support, guaranteed response times, or long-term maintenance commitments.

## Supported versions

Support is defined per repository.

Unless a project explicitly states otherwise, assume:

- the default branch is the main development target;
- the latest release may receive fixes;
- old releases may not receive backports;
- experimental interfaces may change as part of a security fix.

A repository-specific `SECURITY.md` overrides this document.

## Reporting a vulnerability

**Do not open a public issue for an undisclosed vulnerability.**

Use GitHub's private vulnerability reporting / Security Advisory feature for the affected repository when available.

A useful report includes:

- affected repository;
- version, tag, or commit;
- affected component;
- reproduction steps;
- impact;
- proof of concept, if appropriate;
- possible mitigation, if known.

Please keep reports reproducible and focused.

## Scope

Finding a bug in an 0xidle project does not give permission to attack systems operated by:

- users;
- cloud providers;
- API providers;
- model providers;
- GitHub;
- other third parties.

Only test systems you own or are explicitly authorized to test.

Do not unnecessarily access, retain, modify, or expose other people's data.

## Disclosure

We prefer coordinated disclosure.

If a vulnerability is valid, we'll try to understand it, fix it where practical, and disclose enough information for affected users to evaluate the risk.

Because this is a hobby organization, we cannot promise a specific response or remediation deadline.

If a project is abandoned, archived, or otherwise unsupported, we may say so rather than pretending it is actively maintained.

## Bug bounties

There is no organization-wide bug bounty program.

Do not assume monetary compensation unless a repository explicitly offers it.
