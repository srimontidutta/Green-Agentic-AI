# Agentic Energy Taxonomy

The taxonomy lists workflow primitives that can affect computational work, network access, storage access, external execution, latency, or repeated processing.

| Primitive | Energy driver | Disclosure field |
|---|---|---|
| Task classification | Classifier or model call | Task and risk class |
| Retrieval | Embedding, search, storage, network | Retrieval count; cache hit/miss |
| Planning | Reasoning tokens; planner calls | Planning depth or class |
| Generation | Model tier; context and output length | Model tiers; token class |
| Tool execution | API, browser, database, I/O | Tool-call count and type |
| Code execution | Sandbox compute; repeated tests | Code-run count |
| Verification | Additional model or tool calls | Verifier count and type |
| Retry | Multiplicative calls and tokens | Retry count and reason |
| Memory access | Storage access, retrieval cost, write frequency | Memory read/write count |
| Multi-agent coordination | Parallel or sequential model calls | Agent count; debate flag |
| Human escalation | Latency, operational cost, review effort | Escalation flag |

The taxonomy provides a reporting vocabulary. It leaves the numerical relationship between these fields and measured energy to later telemetry and calibration work.
