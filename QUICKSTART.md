# Quick start

An Agent Trajectory Card can usually be prepared from information already available in agent orchestration logs.

## 1. Identify the reporting unit

Record whether the card describes a single run, deployment class, benchmark suite, or production aggregate.

## 2. Describe the goal and workflow

Record the goal type, risk class, contract used, and main workflow pattern.

## 3. Record observable trajectory fields

Capture model calls and tiers, token class, retrievals, cache behavior, tools, code runs, verification, retries, memory events, multi-agent coordination, escalation, and latency where those events occur.

The event-log template in [`templates/trajectory-events.csv`](templates/trajectory-events.csv) can be used when the platform exposes event-level traces.

## 4. Assign the energy proxy class

Use [`reference/energy-proxy-classes.md`](reference/energy-proxy-classes.md) and keep the class consistent with the recorded trajectory.

## 5. Record telemetry, overrides, and uncertainty

State whether direct telemetry was available, record any safety override, and report uncertainty where the energy attribution remains approximate.

## 6. Choose the reporting depth

- [`cards/minimal-card.yaml`](cards/minimal-card.yaml) for lightweight reporting.
- [`cards/machine-readable-card.yaml`](cards/machine-readable-card.yaml) for the standard structured record.
- [`cards/audit-grade-card.yaml`](cards/audit-grade-card.yaml) when configuration, provider, region, timestamps, telemetry hooks, or policy overrides are linked to the trajectory.

## 7. Review the completed record

Use [`CHECKLIST.md`](CHECKLIST.md) before releasing the card or using it to support a sustainability claim.
