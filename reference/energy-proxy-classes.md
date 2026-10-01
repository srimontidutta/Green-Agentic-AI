# Energy proxy classes

The paper defines five coarse trajectory categories for reporting when direct telemetry is unavailable or inaccessible.

| Class | Description |
|---|---|
| **A** | Cache, template, or simple retrieval with minimal generation |
| **B** | Short small-model generation with no tools or retries |
| **C** | Moderate model use, limited retrieval or tools, and limited verification |
| **D** | Large-model use, long context, multiple tools, verification, or retries |
| **E** | Multi-agent debate, repeated retries, code execution, large-context reasoning, or high orchestration overhead |

Assign the class from the observable trajectory fields recorded in the card. The classes support disclosure and comparison; joule-level interpretation requires direct measurement or empirical calibration.
