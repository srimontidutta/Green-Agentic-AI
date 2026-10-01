# Research-agent example

The paper compares two research-agent trajectories that produce a technical summary with citations.

The first trajectory uses a large model, broad search, several retrieved documents, citation verification, a failed verification step, a search retry, and regeneration. The second uses an energy-aware contract with cache checking, authoritative retrieval, small- or medium-model synthesis, one targeted verifier, and escalation only when uncertainty or verifier failure requires it.

The YAML files reproduce the trajectory fields reported in the paper and provide ready-to-use examples of the disclosure format.
