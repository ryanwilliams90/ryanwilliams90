# Ryan Williams

Distinguished Software Engineer @ Rapid7 — AI and data platforms at scale, security systems architecture.

I work on the systems layer beneath AI products — orchestration boundaries, agent identity, runtime governance, provenance, deployment safety, and the operational control planes that make AI systems safe, observable, and accountable in production. My recent work focuses on the primitives this layer needs: where the runtime boundary lives, what unit of identity authorizes a tool call, what the audit chain attests to, and how a deployed artifact carries its own provenance.

## Where to read

- **[Engineering portfolio](https://github.com/ryanwilliams90/portfolio)** — architecture studies and reference implementations across the operational substrate of production AI systems: runtime boundaries, agent identity, code-review orchestration, and provenance. Structured as architecture review, not marketing. Status declared at the top of each case study.
- **[Orchestration gateway pattern](https://github.com/ryanwilliams90/orchestration-gateway-pattern)** — reference implementation of a production AI orchestration boundary. Async edge, bounded synchronous runtime, admission control, ContextVar propagation, lifecycle-scoped secrets, three-layer observability. `mypy --strict`, `ruff` clean, 90+ contract-driven tests including a real-uvicorn smoke test.
- **[Agent identity / MCP credential plane](https://github.com/ryanwilliams90/agent-identity-mcp)** — reference credential plane for agentic systems. Ed25519-signed scoped credentials, verifier-side authorization separated from tool code, replay protection, audience binding, and tool-call identity boundaries. Demonstrates that a credential issued for one action cannot be used to call another.

## Focus areas

- **Production AI infrastructure** — orchestration gateways, runtime boundaries, admission control, operational contracts.
- **Agent identity and authorization** — scoped credentials, action binding, verifier-side policy, replay resistance.
- **AI-assisted SDLC governance** — review orchestration, provenance, attestation, deployment traceability.
- **Supply-chain security** — SLSA, in-toto / DSSE, Sigstore, OCI referrers, VSA-style release verification, admission policy.
- **Distributed data systems** — Apache Iceberg + Trino lakehouse architecture, retrieval and evaluation pipelines, large-scale security telemetry.
- **Security systems** — SOC alert dispositioning, detection metadata enrichment, vulnerability risk scoring.

## How I work

Architecture-first. Constraints and failure modes drive design, not framework choices. I prefer narrow interfaces, explicit runtime boundaries, and systems that fail in observable ways. The case studies emphasize the *why* — what was given up, what failure modes were considered, what the system does when a dependency degrades — over the *what*.

## Contact

- Email: ryan90@gmail.com
- LinkedIn: [ryan-williams-066b5a18](https://www.linkedin.com/in/ryan-williams-066b5a18/)
