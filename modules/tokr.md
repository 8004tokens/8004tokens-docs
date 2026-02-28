# Tokr Module

## What is Tokr?

**Tokr** is the tokenization agent of 8004tokens.

It is purpose-built for ERC-8004 and executes a standardized flow that allows ecosystem participants to create matched tokens for agents.

## Core Value

Tokr transforms trust and attention around an agent into an explicit economic coordination surface.

This allows communities to move from:

- passive observation of agents
- to active economic participation around agents.

## Token Mechanics (Key Rule)

Tokr-issued agent tokens follow a strict, user-visible rule:

- **LP is permanently locked**
- **Trading fee is 1% per swap to the current agent owner**

This is a core binding between token activity and the underlying ERC-8004 agent relationship.

## Public Interaction Model

At a high level, tokenization requests are submitted through structured feedback conventions.

Current request format:

- `tag1 = token-create`
- `tag2 = <network>:<targetAgentId>`

Example:

- `tag1 = token-create`
- `tag2 = base:300`

## Execution Behavior (High-Level)

When Tokr processes a valid request, the flow includes:

1. Validate request format and target information
2. Verify tokenization eligibility and uniqueness constraints
3. Execute tokenization through configured on-chain factory paths
4. Write back result status to the corresponding interaction thread

## Design Goals

- Permissionless participation for requests
- Deterministic and auditable execution path
- Clear result feedback to users
- Modular integration with discovery and trust layers

## Tokr in the Platform Loop

- **Agents** helps discover candidates
- **Agent8** adds trust context
- **Tokr** executes tokenization
- **Tokens** route exposes market-facing token views tied back to agent context

## Important Naming Note

- Public name: **Tokr**
- Internal service/process names may vary by environment and repository

## Next Read

- [User Journeys](../user-journeys.md)
- [Trust, Safety, and Execution Boundaries](../trust-safety.md)
