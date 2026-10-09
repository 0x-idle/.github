# 0x1d1e

**software made during idle cycles.**

A loose group of people building things in hobby time, unemployed time, weekends, late nights, or whenever there are spare CPU cycles.

We mostly mess with:

- AI / LLM infrastructure
- developer tools
- agents and automation
- Linux desktop software
- interfaces
- infrastructure
- applied ML research, especially Khmer language technology
- whatever seems interesting next

[Website](https://0x1d1e.tech) · [Repositories](https://github.com/orgs/0x1d1e/repositories)

## What we're building

| Project | What it is |
| --- | --- |
| [Kanade](https://github.com/0x1d1e/kanade) | A top-center Dynamic Island and desktop shell experience for [niri](https://github.com/YaLTeR/niri), built with Amane. |
| [Kinetix](https://github.com/0x1d1e/kinetix) | A self-hosted LLM gateway for coding agents and small teams: compatible APIs, routing, fallback, account pools, and usage tracking. |
| [Kinetix Plugins](https://github.com/0x1d1e/kinetix-plugins) | Plugins, SDK, and tooling for extending Kinetix through WebAssembly. |
| [Khmer Decision Lab](https://github.com/0x1d1e/khmer-decision-lab) | Reproducible research on lightweight Khmer language understanding, decision models, fine-tuning, and evaluation on consumer GPUs. |

The repositories are at different stages. Some are actively changing, some are experiments, and some may be paused or archived. Check each project's README for its current state.

## Research

Not every useful result is an app.

[Khmer Decision Lab](https://github.com/0x1d1e/khmer-decision-lab) starts with Khmer intent classification and small decision models. The broader questions include cross-task generalization, OCR robustness, retrieval relevance, calibration, latency, and memory use.

We want research that can be checked: documented datasets and splits, reproducible experiments, baselines, error analysis, and negative results when an idea doesn't work.

A benchmark result is evidence for the task and setup that produced it—not a claim that a model works everywhere.

## Why

Most projects here start with some variation of:

> "what if we just built it?"

Sometimes that produces a useful tool.

Sometimes it produces a prototype that answers one question and is never touched again.

Both are valid outcomes.

## How we work

### Build first

Working software usually teaches us more than discussing hypothetical software.

### Verify things

If something depends on an assumption, test it.

Source code, benchmarks, traces, reproductions, real usage, and measurements beat guesses.

### Keep the useful parts

Experiments are allowed to fail.

When something works well enough to keep, we gradually make it less cursed.

### No fake stability

A project being public does not mean it is:

- production-ready;
- stable;
- maintained forever;
- backward compatible;
- suitable for your infrastructure.

Check the repository.

### No roadmap theater

Projects move when someone wants to work on them.

Issues and roadmaps describe intent, not contractual delivery dates.

## Project status

Unless a repository explicitly says otherwise, assume:

> **experimental — APIs may break, designs may change, dragons possible.**

Individual repositories define their own stability, releases, compatibility guarantees, and support expectations.

## Contributing

Bug reports, experiments, fixes, criticism, benchmarks, weird ideas, and good pull requests are welcome.

Repository-specific instructions override the organization defaults.

See [CONTRIBUTING.md](../CONTRIBUTING.md).

## Security

Please don't put vulnerabilities in public issues.

See [SECURITY.md](../SECURITY.md).
