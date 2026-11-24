# Stefan Wiest Research Lab

<div align="center">
  <img src="https://github.com/stefanwiest/assets/blob/main/branding/stefanwiest_ringed_giant_logo.png" alt="The Ringed Giant" width="128">
  <br>
  <b>Post-Harness Multi-Agent Coordination, Control Protocols &amp; Systems Architecture</b>
</div>

---

## Research Focus

I research and specify deterministic coordination protocols and hardware-inspired concurrency invariants for production multi-agent systems, backed by 16+ years of distributed systems engineering.

> **"Orchestration is explicit. Coordination is emergent."**

Every coordination primitive pairs directly with enterprise runtime controls: `CUE` (deterministic task dispatch), `FERMATA` (blocking human-in-the-loop approval hold for EU AI Act Art. 14 and OWASP ASI02), `CAESURA` (emergency circuit breaker and kill switch for OWASP ASI04/ASI08), `VAMP` (deterministic quality retry gate), and `MESI` state coherency (eliminating parallel write races).

### Core Repositories

| Project | Description | Control Role |
| :--- | :--- | :--- |
| **[hct-spec](https://github.com/stefanwiest/hct-spec)** | Single-source `spec.yaml` generating Python, TypeScript, Rust, Go, and Protobuf coordination schemas. | *Canonical Spec* |
| **[hct-mcp-signals](https://github.com/stefanwiest/hct-mcp-signals)** | Coordination signal extensions for Anthropic Model Context Protocol (MCP). | *MCP Governance* |
| **[hct-a2a](https://github.com/stefanwiest/hct-a2a)** | Coordination signal extensions for Google Agent-to-Agent (A2A) protocol. | *A2A Mesh Control* |
| **[hct-patterns](https://github.com/stefanwiest/hct-patterns)** | 15 diagnostic failure modes and mitigations for multi-agent deployments. | *Failure Taxonomy* |

*Reference architecture materials (`hct-core` and the Genesis Framework) are documented publicly under Publications &amp; Essays below.*

---

## Publications &amp; Essays

- **[Architectural Convergence (2026)](https://www.stefanwiest.de/research/papers/architectural-convergence/):** Mapping Tomasulo, MESI, and DVFS hardware patterns onto multi-agent systems (2.6x speedup, 100% state coherency).
- **[Harmonic Coordination Theory (2025)](https://www.stefanwiest.de/research/papers/harmonic-coordination-theory/):** 6-layer coordination stack and 7 deterministic control signals.
- **[The Genesis Framework (2025)](https://www.stefanwiest.de/research/papers/genesis-framework/):** Reference DAG execution and verification-refinement loops.
- **[The Raptor Law of AI Agents (2026)](https://www.stefanwiest.de/writing/essays/raptor-law-of-ai-agents/):** Why frontier model generations absorb thin harnesses and require durable control planes.
- **[The 97% Problem](https://www.stefanwiest.de/writing/essays/97-percent-problem/):** Why agent pilots stall at coordination Layers 3 through 5.

---

## More from Stefan Wiest

- **Advisory &amp; Audits:** [stefanwiest.de/advisory](https://www.stefanwiest.de/advisory/)
- **Production Track Record:** [stefanwiest.de/work](https://www.stefanwiest.de/work/)
- **Personal Engineering Hub:** [github.com/skew202](https://github.com/skew202)
- **Verification Tooling:** [antislop](https://github.com/skew202/antislop) · [envcheck](https://github.com/envcheck) · [nerfstatus](https://github.com/nerfstatus)
- **Hugging Face:** [huggingface.co/stefanwiest](https://huggingface.co/stefanwiest)
- **Substack Column:** [seekingsota.substack.com](https://seekingsota.substack.com)
