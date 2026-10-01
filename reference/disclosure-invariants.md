# Disclosure invariants

The protocol uses five invariants to keep sustainability claims traceable to the reported trajectory.

1. **Identify the reporting unit.** State whether the claim covers a single run, deployment class, benchmark suite, or production aggregate.
2. **Support the proxy class with trajectory fields.** Keep tool use, verification, retries, code execution, and multi-agent coordination visible in the record.
3. **Maintain claim-to-card traceability.** Link a sustainability claim to the corresponding contract, proxy fields, and telemetry status.
4. **Report safety overrides.** Record cases in which safety or other required checks override an energy-saving constraint.
5. **Report uncertainty.** Include uncertainty when direct telemetry is unavailable or provider opacity limits attribution.

Together, these fields preserve the operational reasons for a higher-cost trajectory, including verification, escalation, and human review.
