# Agent Trajectory Card fields

The machine-readable card follows the field vocabulary in the paper. Additional descriptive fields connect the card to the taxonomy and disclosure invariants used elsewhere in the protocol.

| Field | Use |
|---|---|
| `reporting_unit` | Single run, deployment class, benchmark suite, or production aggregate |
| `goal_type` | User task category |
| `risk_class` | Low, medium, high, or safety-critical |
| `contract_used` | Sustainability contract or execution rule applied to the trajectory |
| `workflow_pattern` | RAG, tool-using, coding, multi-agent, or another concise architecture description |
| `model_call_count` | Total model invocations |
| `model_tiers` | Relative model classes used during the trajectory |
| `token_class` | Small, medium, large, or very large |
| `retrieval_count` | Number of retrieval operations |
| `cache_status` | Hit, miss, partial, or a short descriptive equivalent |
| `tool_call_count` | Number of external tool or service calls |
| `tool_types` | Tool categories used in the trajectory |
| `code_run_count` | Number of sandbox, script, test, or other code executions |
| `verification_passes` | Number of verification passes |
| `verification_type` | Citation, correctness, safety, policy, or another verifier description |
| `retry_count` | Number of repeated attempts or reflections |
| `retry_reason` | Reason for retry where applicable |
| `memory_events` | Number of memory reads or writes when recorded as a combined count |
| `multi_agent.agent_count` | Number of participating agents where applicable |
| `multi_agent.debate_flag` | Whether a debate-style multi-agent pattern was used |
| `escalation_flag` | Whether the workflow escalated to a higher tier or human review |
| `latency_class` | Low, medium, or high |
| `energy_proxy_class` | A, B, C, D, or E |
| `carbon_aware_scheduling` | None, batchable, carbon-aware, or a short descriptive equivalent |
| `optimization_note` | Suggested change to the trajectory |
| `safety_override` | Whether a safety or risk requirement overrode an energy-saving constraint |
| `telemetry_available` | Whether direct energy telemetry was available for the reported trajectory |
| `uncertainty` | Low, medium, or high uncertainty in the proxy disclosure |

The `reporting_unit`, tool-type, verifier-type, retry-reason, multi-agent, and escalation fields carry information already represented in the taxonomy or disclosure invariants and make cross-study records easier to interpret.
