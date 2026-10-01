# Protocol evaluation criteria

The paper proposes five criteria for evaluating trajectory-level energy disclosure.

| Criterion | Question |
|---|---|
| **Coverage** | Does the taxonomy capture the main energy-relevant workflow events, including model calls, retrieval, tools, code execution, verification, retries, memory, and multi-agent coordination? |
| **Actionability** | Do reported fields map to control levers such as routing, token budgets, retry caps, verifier triggers, or cache policy? |
| **Comparability** | Can systems with similar final outputs be distinguished by their hidden trajectories? |
| **Auditability** | Can benchmark maintainers, deployment owners, or governance reviewers inspect the record without relying on proprietary provider internals? |
| **Safety preservation** | Does energy-aware execution preserve required verification, refusal, escalation, or human review for higher-risk tasks? |

These criteria can be used when designing a benchmark, reviewing a reporting implementation, or comparing disclosure practices across agent systems.
