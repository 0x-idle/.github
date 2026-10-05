# Contributing to 0x1d1e

0x1d1e is a collection of experiments and projects built in spare time.

Contributions are welcome, but don't expect corporate process.

Repository-specific instructions always take precedence over this file.

## Before changing things

Understand what the repository is trying to do.

Some projects are:

- quick experiments;
- active prototypes;
- maintained tools;
- research spikes;
- mostly finished;
- effectively abandoned but still useful as reference.

The appropriate amount of engineering depends on which one you're touching.

For a small obvious fix, open a pull request.

For a major redesign, new subsystem, dependency change, or behavior that affects the project's direction, opening an issue first is usually useful.

## General rules

### Solve the actual problem

Avoid turning a small fix into:

- an architecture rewrite;
- dependency churn;
- unrelated cleanup;
- speculative abstraction;
- a framework migration nobody asked for.

If another problem deserves fixing, make it another change.

### Bring evidence

When relevant, include:

- tests;
- reproductions;
- benchmarks;
- logs;
- traces;
- screenshots;
- upstream documentation;
- source references;
- real-world verification.

"I think this should work" is weaker than "here is what happened."

### Failed experiments are valid

If an idea doesn't work, say so.

A good negative result can be more useful than forcing an implementation to satisfy the original assumption.

### Keep important behavior explicit

Prefer clear:

- ownership;
- state transitions;
- invariants;
- interfaces;
- failure modes;
- compatibility rules.

Avoid magic behavior and accidental coupling where possible.

### Keep PRs reviewable

A pull request should make it reasonably easy to understand:

1. what was wrong or missing;
2. what changed;
3. why this approach was chosen;
4. how it was tested;
5. what remains intentionally unresolved.

Don't write an essay when the diff is obvious.

Don't write "fixed stuff" when it isn't.

## Tests

Add tests when they protect behavior worth keeping.

Good targets include:

- regressions;
- public interfaces;
- invariants;
- state transitions;
- serialization and persistence;
- compatibility boundaries;
- error handling;
- recovery behavior.

Avoid tests that simply mirror private implementation details.

Run the repository's documented formatting, linting, tests, and checks before submitting.

## Compatibility

Unless explicitly promised by a repository, compatibility is not sacred.

Experimental projects may break:

- APIs;
- configuration;
- schemas;
- persisted state;
- protocols;
- internal architecture.

But breaking something should still be intentional and documented.

"Experimental" is not an excuse for accidental breakage.

## Dependencies

Don't add a dependency because writing ten lines of code felt boring.

Don't reimplement a complicated, well-maintained dependency because adding dependencies feels impure either.

Use judgment.

Consider:

- maintenance;
- security;
- binary size;
- compile/build cost;
- transitive dependencies;
- portability;
- whether the dependency actually solves enough of the problem.

## AI-assisted contributions

AI-generated or AI-assisted contributions are allowed.

You are still responsible for what you submit.

That includes:

- understanding the change;
- reviewing generated code;
- testing it;
- checking provenance and licenses;
- removing hallucinated or irrelevant content;
- ensuring the implementation actually solves the problem.

"The agent said it passes" is not verification.

## Security

Do not publicly disclose unresolved vulnerabilities.

Follow `SECURITY.md`.

## Conduct

Be technical and specific.

Disagree with ideas freely.

Do not turn technical disagreement into attacks on people.

Nobody here is required to pretend every idea is good.

The point is to experiment, figure out what works, and keep the interesting parts.
