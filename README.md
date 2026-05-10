# Ryan Williams

Senior engineer working on production AI infrastructure: orchestration, runtime governance, agent identity, provenance, and the operational systems around model-driven workflows.

I work on the seam between AI runtimes and the security, reliability, and governance posture organizations need around them. Most of my recent thinking is about runtime boundaries, secure agent execution, and the observability story for systems that don't fit standard stateless-API assumptions.

## Where to read

- **[Engineering portfolio](https://github.com/ryanwilliams90/portfolio)** — case studies, architecture writeups, and engineering notes. Structured as an architecture review, not a marketing site.
- **[Orchestration gateway pattern](https://github.com/ryanwilliams90/orchestration-gateway-pattern)** — companion code to the gateway case study. A clean-room reference implementation of the async/sync executor-boundary pattern: `mypy --strict`, `ruff` clean, 80+ contract-driven tests including a real-uvicorn smoke test.

## Areas of focus

- AI orchestration and runtime systems — gateways, model routing, runtime boundaries, agent execution
- Identity and credential planes — agent identity, scoped credentials, MCP-compatible tool access
- Provenance and attestation — cryptographic provenance for AI-assisted code, deployment governance
- Distributed systems and data platforms — Apache Iceberg + Trino lakehouse work, retrieval and evaluation pipelines
- Operational reliability — observability, failure modes, runtime concerns for AI systems in production

## How I work

Architecture-first. Constraints and failure modes drive design, not framework choices. I prefer narrow interfaces, explicit runtime boundaries, and systems that fail in observable ways.
