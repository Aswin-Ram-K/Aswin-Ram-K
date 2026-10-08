# Aswin Ram Kalugasala Moorthy

**Agent-infrastructure engineer — harnesses, sandboxes, and control planes for LLM systems.**

Chicago, IL · M.A.S. ECE, Illinois Institute of Technology (Fall 2027 expected) · B.Tech ECE, NIT Karnataka

I work on the layer underneath model behaviour: how a state transition decides which model, context
and tools exist for the step it is about to run, and how an enforcement boundary holds by *absence*
rather than by refusal. Where I can, I measure the claim instead of asserting it.

## Featured

| Project | What it is |
|---|---|
| **[Consonance](https://github.com/Aswin-Ram-K/Consonance)** | Capability-materialisation kernel for agent runtimes. Each state transition materialises exactly the grants a step needs and revokes them on the next. Enforcement by absence, not refusal. A live A/B holds everything constant except the state class — and the workspace digest stays byte-identical when the capability is absent. |
| **[meta-agent](https://github.com/Aswin-Ram-K/meta-agent)** | Review-first, self-hosted control plane for designing, observing and reviewing multi-agent workflows. FastAPI + PostgreSQL + Temporal + React. |

More: [Valhalla](https://github.com/Aswin-Ram-K/Valhalla) (local-first agent platform) ·
[Alfred](https://github.com/Aswin-Ram-K/alfred) (autonomous coursework assistant with a one-approval
gate) · [WEBSEER](https://github.com/Aswin-Ram-K/WEBSEER) (meta-search design study, Rust) ·
[ticket-fleet](https://github.com/Aswin-Ram-K/ticket-fleet) (the issue tracker as the fleet's work
queue and control plane).

## How I work

I would rather ship a number I ran than a claim I believe. Several of the most useful things I have
learned came from an experiment falsifying a result I liked — including a token-saving win that its
own pre-registered control voided. Where a suite passes and the real corpus disagrees, I trust the
corpus and go find out which one was lying.

- TypeScript / Python / Rust · bubblewrap, capability-based security, Merkle-DAG state
- Node ≥24, FastAPI, PostgreSQL, Temporal, SQLite, Docker, Linux
- Pre-registered experiments · append-only ledgers · falsifiers written before the code runs

## Contact

kaswinram.1603@gmail.com · Open to summer 2027 internship and new-graduate roles in agent
infrastructure and forward-deployed engineering.
