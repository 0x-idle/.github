# Contributing to PrightCord

Thank you for your interest in contributing to PrightCord projects! We build high-reliability, low-latency infrastructure for AI inference and developer workflows.

## General Guidelines

1. **Protocol & Semantic Accuracy**: Preserving upstream protocol fidelity and streaming behavior is paramount across our proxies and tools.
2. **Quality & Test Coverage**: Every bug fix should include a regression test. Every new feature should include comprehensive unit and smoke tests.
3. **Security First**: Never check in secrets, credentials, or production tokens. All dependencies must pass license and vulnerability screening.
4. **Clean Git History**: Use descriptive commit messages following the Conventional Commits specification (`feat:`, `fix:`, `chore:`, `docs:`, etc.).

## Workflow

1. Fork the repository (or create a feature branch if you are a collaborator).
2. Create a focused branch: `git checkout -b feature/your-feature-name`.
3. Verify formatting, linter, and tests locally:
   - For Rust crates: `cargo fmt --check && cargo clippy --all-targets && cargo test`
   - For Node / TypeScript packages: `npm ci && npx tsc --noEmit && npm run build`
4. Open a Pull Request referencing any related issues and following our PR template.
