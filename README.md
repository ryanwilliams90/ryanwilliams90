# Ryan Williams

Distinguished Software Engineer @ Rapid7 — AI and data platforms at scale, security systems architecture.

I work at the seam between AI runtimes and the security, reliability, and governance posture that real organizations need around them. Most of my recent thinking is about runtime boundaries, secure agent execution, agent identity, and the observability story for systems that don't fit standard stateless-API assumptions.

This profile is a working set of architecture writeups and reference code, not a CV. The portfolio repo is the primary surface; the prototype repos are companion code so a reader can verify the patterns described in the case studies are grounded in working software.

## Where to read

- **[Engineering portfolio](https://github.com/ryanwilliams90/portfolio)** — case studies, architecture writeups, and engineering notes. Structured as an architecture review, not a marketing site. Status (`Shipped` / `Prototype` / `Design`) is declared at the top of each case study.
- **[Orchestration gateway pattern](https://github.com/ryanwilliams90/orchestration-gateway-pattern)** — companion code to the gateway case study. Clean-room reference implementation of the async/sync executor-boundary pattern: `mypy --strict`, `ruff` clean, 80+ contract-driven tests including a real-uvicorn smoke test.

## Areas of focus

- **AI orchestration and runtime systems** — gateways, model routing, runtime boundaries, agent execution
- **Identity and credential planes** — agent identity, scoped credentials, MCP-compatible tool access
- **Provenance and attestation** — cryptographic provenance for AI-assisted code, deployment governance
- **Distributed data systems** — Apache Iceberg + Trino lakehouse architecture, retrieval and evaluation pipelines, large-scale security telemetry
- **Operational reliability** — observability, failure modes, runtime concerns for AI systems in production
- **Security systems** — SOC alert dispositioning, detection metadata enrichment, vulnerability risk scoring

## How I work

Architecture-first. Constraints and failure modes drive design, not framework choices. I prefer narrow interfaces, explicit runtime boundaries, and systems that fail in observable ways. The case studies emphasize the *why* — what was given up, what failure modes were considered, what the system does when a dependency degrades — over the *what*.

## Contact

- Email: ryan90@gmail.com
- LinkedIn: [ryan-williams-066b5a18](https://www.linkedin.com/in/ryan-williams-066b5a18/)
