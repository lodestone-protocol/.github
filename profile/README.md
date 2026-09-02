# Lodestone Protocol

**A language-agnostic protocol for embedding DAG metadata in CommonMark, enabling agent conversational knowledge convergence.** Alias: MD-DAG.

📖 Specification · [Reference Implementation (Rust)](https://github.com/lodestone-protocol/lodestone-md) · [Releases](https://github.com/lodestone-protocol/lodestone-spec/releases)

---

## What is Lodestone?

Lodestone Protocol (alias MD-DAG) defines a minimal, deterministic way to embed machine-readable DAG metadata into CommonMark documents via HTML comments. It is designed for AI agent systems that need a **shared, conflict-free, file-is-current-state knowledge surface** across multiple agents and sessions.

- **Current version**: v1.3.0 (Final, frozen) — see the [Release](https://github.com/lodestone-protocol/lodestone-spec/releases/tag/v1.3.0)
- **Base standard**: CommonMark 0.31.2
- **Compliance badge**: 25 Golden Fixtures, 14/14 diagnostic codes exercised

## Repositories

| Repository | Role | License |
|---|---|---|
| [lodestone-spec](https://github.com/lodestone-protocol/lodestone-spec) | Protocol specification, error code registry, Golden Fixtures (authoritative source) | Apache-2.0 |
| [lodestone-md](https://github.com/lodestone-protocol/lodestone-md) | Rust reference implementation (23 tests, clippy-clean) | MIT |

Future per-language implementations (`lodestone-py`, `lodestone-ts`, …) will be added here as third-party demand emerges.

## Getting started

1. Read the [specification](https://github.com/lodestone-protocol/lodestone-spec/blob/main/spec/v1.3.md) (start with §1–§3 for philosophy and syntax)
2. Try the [Rust reference implementation](https://github.com/lodestone-protocol/lodestone-md#quick-start)
3. Pull the [Golden Fixtures](https://github.com/lodestone-protocol/lodestone-spec/tree/main/fixtures) to validate your own implementation in any language

## Contributing

- **Specification changes**: open an issue in [lodestone-spec](https://github.com/lodestone-protocol/lodestone-spec/issues) — protocol is at v1.3 Final, changes require ADR-level discussion
- **Reference implementation bugs**: open an issue in [lodestone-md](https://github.com/lodestone-protocol/lodestone-md/issues)
- **ADR boundaries**: see [lodestone-spec/CONTRIBUTING.md](https://github.com/lodestone-protocol/lodestone-spec/blob/main/CONTRIBUTING.md)

## Code of Conduct & Security

Be excellent to each other. Security issues should be reported privately via GitHub Security Advisories on the affected repository, not via public issues.

---

🌐 [简体中文](./README.zh-CN.md) · Lodestone Protocol is an independent open-source project.
