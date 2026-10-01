# Energy-aware disclosure protocol

The protocol reports energy-relevant agent behavior at the trajectory level. An agent trajectory includes the operations used to complete a goal: task classification, planning, model calls, retrieval, tool execution, code runs, observations, memory reads or writes, verification, retries, escalation, and final-response steps.

The protocol has three linked parts:

1. the **Agentic Energy Taxonomy** identifies energy-relevant workflow events;
2. the **Agentic Sustainability Contract** records execution constraints and escalation conditions;
3. the **Agent Trajectory Card** records the resulting trajectory.

## 1. Identify the trajectory

Choose the reporting unit before filling out the card. The paper uses an agent run or deployment class as the principal reporting object. Benchmark suites and production aggregates can also be reported when the reporting unit is stated clearly.

## 2. Classify energy-relevant events

Use the taxonomy to identify the workflow primitives that occurred. The taxonomy records the event and the corresponding disclosure field rather than assigning a fixed energy weight.

## 3. Record the sustainability contract

The contract captures the execution rules applied before or during the workflow:

- task and risk class;
- model-tier budget;
- token budget;
- tool and code budget;
- retrieval and cache rule;
- retry budget;
- verification rule;
- escalation rule;
- disclosure rule.

A contract can encode patterns such as cache-first reuse, retrieve-first grounding, small-first routing, escalation on uncertainty, verification for higher-risk tasks, capped retries, batching where appropriate, and human review for critical tasks.

## 4. Complete the Agent Trajectory Card

The standard card records:

- goal type;
- risk class;
- contract used;
- workflow pattern;
- model tiers used;
- model-call count;
- token class;
- tool-call count;
- retrieval and cache use;
- code execution;
- verification passes;
- retries or reflections;
- memory access;
- latency class;
- energy proxy class;
- carbon-aware scheduling;
- safety override;
- uncertainty;
- optimization note.

Direct energy measurements can be attached when telemetry is available. Proxy fields remain useful for comparison when hardware-level or provider-level measurements are unavailable.

## 5. Assign the proxy class

The paper defines coarse classes A–E. The classification should be supported by the observable trajectory fields recorded in the card.

## 6. Apply the disclosure invariants

Sustainability claims should state the reporting unit, remain traceable to the corresponding trajectory record, show the observable basis for any proxy class, report safety overrides, and disclose uncertainty when direct telemetry is unavailable.

## 7. Select a reporting depth

Use the minimal, standard, or audit-grade form according to the reporting purpose. The same core vocabulary is retained across all three levels.

## 8. Compare or audit

Completed cards can be compared across agent configurations, benchmark conditions, or deployment classes. The paper proposes five criteria for evaluating the quality of trajectory-level disclosure: coverage, actionability, comparability, auditability, and safety preservation.
