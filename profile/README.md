# PrightCord

> **Intelligent LLM Gateway, Routing & Inference Acceleration Infrastructure.**

PrightCord designs high-performance, streaming-first developer tooling and proxy infrastructure for the generative AI era. Our mission is to keep your LLM traffic resilient, private, and fully under your control.

---

### 🚀 Core Projects

* **[kinetix](https://github.com/PrightCord/kinetix)** — Streaming-first LLM reverse proxy and routing engine.
  * Smart latency-aware and tier-based failover across multiple model providers.
  * Real-time SSE streaming aggregation and protocol translation.
  * Dynamic virtual key management and tenant quota enforcement.
  * Embedded, zero-dependency admin dashboard built with Rust and React.
* **[kinetix-plugins](https://github.com/PrightCord/kinetix-plugins)** — Official and community WebAssembly (WASM) plugins.
  * Extend proxy behavior with sandboxed, low-overhead request/response interceptors.
  * WIT-defined component model ensuring strict ABI stability.
* **[kinetix-frontend](https://github.com/PrightCord/kinetix-frontend)** — Web dashboard and UI interface.
  * Live metrics, token consumption analytics, route configuration, and virtual key provisioning.

---

### 🛡️ Security & Reliability

* **Confidentiality by Design**: Virtual keys prevent upstream API secret exposure to downstream clients.
* **Supply Chain Integrity**: Strict dependency vulnerability scanning and license enforcement.
* **Responsible Disclosure**: If you discover a potential security vulnerability, please report it privately via [GitHub Security Advisories](https://github.com/PrightCord/kinetix/security/advisories/new).

---

### 🤝 Contributing

We welcome contributions from the community!
- Check out the [Contributing Guidelines](https://github.com/PrightCord/kinetix/blob/main/CONTRIBUTING.md) to get started.
- Follow our coding standards: protocol fidelity, minimal latency overhead, and test-driven fixes.
