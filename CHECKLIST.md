# Reporting checklist

Use this checklist when preparing an Agent Trajectory Card or a sustainability statement based on the protocol.

## Reporting unit

- [ ] The record identifies whether it describes a single run, deployment class, benchmark suite, or production aggregate.
- [ ] The reported fields correspond to the same reporting unit.

## Trajectory

- [ ] Model calls and model tiers are reported.
- [ ] Token volume is reported as a class when exact counts are not used.
- [ ] Retrieval and cache behavior are reported where applicable.
- [ ] Tool calls and code executions are reported where applicable.
- [ ] Verification passes and retries are reported where applicable.
- [ ] Memory events and multi-agent coordination are reported where applicable.
- [ ] Escalation or human review is recorded when it occurs.

## Contract

- [ ] Model-tier and token constraints are recorded where a sustainability contract was used.
- [ ] Tool/code and retry limits are recorded where applicable.
- [ ] Retrieval/cache, verification, and escalation rules are recorded.
- [ ] The selected disclosure depth matches the card being released.

## Proxy reporting

- [ ] The energy proxy class is supported by the observable trajectory fields.
- [ ] The proxy class is presented as a disclosure category rather than a calibrated energy measurement.
- [ ] Direct telemetry, when available, is kept distinguishable from proxy information.

## Traceability

- [ ] A sustainability claim can be traced to the corresponding Agent Trajectory Card.
- [ ] Safety overrides are reported.
- [ ] Uncertainty is reported when direct telemetry or provider-level attribution is unavailable.
