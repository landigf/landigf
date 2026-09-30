# Gennaro Francesco Landi

MSc Computer Science @ ETH Zürich

Systems, ML infrastructure, and backend engineering.

I build measurement tools and typed AI workflows, with an emphasis on reproducible evaluation and inspectable behavior. Major in Data Management Systems, minor in Machine Learning. Available full-time from summer 2027.

[Portfolio](https://landigf.github.io/) · [Research & Projects](https://landigf.github.io/research.html) · [Blog](https://landigf.github.io/blog.html) · [LinkedIn](https://www.linkedin.com/in/landigf)

---

## Selected Projects

### CacheRegime: Choosing a Cache Policy from a Request Prefix

A warm-up selector evaluated on seven public cache traces with a WebLINX-derived synthetic agent overlay.

Key research work:

- Leave-one-trace-out evaluation: **59/63 settings correct (93.7%)**.
- Mean human-request hit rate of **13.09%**, versus **12.94%** for the best fixed baseline: **+0.141 percentage points**.
- Reproduction script checks aggregate inputs, refits held-out folds and validates archived predictions.
- Explicit limits: synthetic overlays, a 64 MiB cache budget and unproven transfer to collected agent traffic.

[Repo](https://github.com/landigf/cache-regime-benchmark) · [Results & Write-up](https://landigf.github.io/cache-regime.html) · [Technical Note](https://landigf.github.io/assets/research/cache-regime-report.pdf) · [Slides](https://landigf.github.io/assets/research/cache-regime-presentation.pdf)

---

### BrowseTrace: Measuring Browser-Agent Traffic

Request-level traces and replay tooling for studying the infrastructure behind browser-mediated AI workloads.

Key engineering work:

- Typed request capture, sanitization tools and cache-ready trace exports.
- Public replay inputs: **82,455 scripted request rows** and **357,782 LLM-labelled request rows**.
- Offline evaluation of six cache policies at five capacities, with request and byte hit rates reported separately.
- A release audit that distinguishes observable CSV contents from collection counts the public snapshot cannot verify.

[Repo](https://github.com/landigf/BrowseTrace) · [Results & Write-up](https://landigf.github.io/browsetrace.html) · [Replay Data](https://github.com/landigf/BrowseTrace/blob/main/reports/public-cache-replay.json)

---

### ClaudeFlow: Typed AI Workflows

A TypeScript library for composing AI tasks with Zod schemas, loops, branches and maps.

Key engineering work:

- Runtime schema validation and inspectable execution traces.
- Deterministic mock runtime for testing without inference calls.
- Static pipeline checks and token/cost estimates.
- Reproducible local orchestration benchmarks with raw samples, p50/p95 and clear separation from model latency or quality.

[Repo](https://github.com/landigf/claudeflow) · [Engineering Write-up](https://landigf.github.io/claudeflow.html) · [Benchmark Method](https://github.com/landigf/claudeflow/blob/master/benchmarks/README.md)

---

### AuditChain: START Hack 2026

**First place in the Chain IQ case challenge**, built with a team at START Hack 2026.

A procurement prototype combining language-model parsing with deterministic decision rules and an auditable execution path. The public repository contains the hackathon submission.

[Repo](https://github.com/landigf/auditchain-submission) · [Architecture & Blog Post](https://landigf.github.io/starthack-2026-auditchain.html)

---

### V2X Co-Pilot Data Platform

Bachelor’s thesis work on traffic/weather integration for vehicle assistance: API adapters, spatio-temporal filtering, TTL caching, fuzzy risk scoring and monitoring.

[Repo](https://github.com/landigf/minervas-v2x-copilot-thesis)

---

### Earlier Projects

- [TORCS](https://github.com/landigf/TORCS): behavioral cloning with nearest-neighbor search and KD-tree optimization.
- [Broletter](https://github.com/landigf/Broletter): personalized science delivery using arXiv and Telegram. [Blog post](https://landigf.github.io/Broletter-post.html).

I also contribute to internal infrastructure and backend automation at the ETH Entrepreneur Club.
