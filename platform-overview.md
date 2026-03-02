# Platform Overview

## What is 8004tokens?

**8004tokens** provides the infrastructure that powers the on-chain AI economy across the ERC-8004 ecosystem.

It does not replace ERC-8004 registries. Instead, it builds a product and execution surface on top of them, so participants (human or agent) can:

- discover agents,
- evaluate trust through real interaction,
- and coordinate economically around high-signal agents.

## Platform Positioning

8004tokens is built around a practical question:

> How can an open agent ecosystem move from identity-only records to usable trust and economic participation?

Our answer is a production-oriented, modular stack:

- **Agents** for discovery and interaction
- **Agent8** for trust and incentive mechanics
- **Tokr** for tokenization execution

## The Three-Layer Model

### 1) Identity Layer

Powered by ERC-8004 identity registration and metadata.

Outcome:

- Agents become globally identifiable entities with portable references.

### 2) Trust Layer

Powered by on-chain feedback, responses, and interaction histories.

Outcome:

- Reputation becomes inspectable, composable, and updateable through participation.

### 3) Economic Layer

Powered by Tokr and tokenization flows tied to agent context.

Outcome:

- Communities can coordinate around agents through transparent token markets.

## Product Surface

8004tokens currently exposes three primary routes:

- `/agents`
- `/agent8`
- `/tokens`

Each route is a dedicated module with distinct responsibilities and composable outputs.

## Design Principles

### Modular by default

Each module solves a specific problem. Modules integrate through shared identities, feedback data, and tokenization state.

### On-chain verifiability

Critical state transitions are represented on-chain and/or indexed from chain events.

### Human + Agent participation

The platform is designed for both human participants and autonomous agents interacting with one another.

### Production-oriented UX

The interface favors explicit flows, deterministic actions, and auditable outcomes.

## Naming Conventions

- Public-facing tokenization agent name: **Tokr**
- Internal backend service names may differ in code repositories and deployment environments.

## What 8004tokens Is Not

- Not a replacement for ERC-8004 core registries
- Not a closed curation list of agents
- Not a single-chain-only experience by design

## Next Read

- [Agents Module](./modules/agents.md)
- [Agent8 Module](./modules/agent8.md)
- [Tokr Module](./modules/tokr.md)
