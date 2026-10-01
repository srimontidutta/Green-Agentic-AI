# Agent Trajectory Cards

The paper defines three reporting depths.

## Minimal

The minimal card records model-call count, model tiers, token class, tool calls, retries, and energy proxy class, together with basic task information.

## Standard

The standard card adds retrieval/cache use, verification, code execution, memory access, latency, uncertainty, optimization notes, and the other fields in the paper's disclosure card.

## Audit-grade

The audit-grade card extends the standard record with trajectory bindings such as timestamps, configuration, provider, region, telemetry hooks, and policy overrides.

All three templates use the same trajectory-level reporting vocabulary.
