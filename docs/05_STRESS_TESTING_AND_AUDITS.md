# Stress Testing and Audits

Alexandria treats system claims as testable.

If the system says it is recoverable, it should be tested after context gaps. If it says navigation is clean, links should be audited. If it says a workflow reduces drift, the relay should be stressed with ambiguity and interruption.

## What Gets Tested

| Area | Example check |
|---|---|
| Navigation | Broken active links, folder map accuracy |
| Note quality | Required headers, purpose lines, stale notes |
| Relay behavior | Agent blocks when context is missing |
| Public safety | No raw state, credentials, paths, or private data in release material |
| Archive health | Heavy logs move out of active space without losing retrieval |
| Recovery | A new agent can reconstruct current state from written files |

## Current Validation Snapshot

June 2026 internal validation:

| Metric | Result |
|---|---:|
| Active broken wikilinks | 0 |
| Missing required note headers | 0 |
| Stale thinking notes older than 60 days | 0 |
| Empty markdown folders | 0 |
| Public/private boundary | Active |
| Relay review loop | Active |

These are not permanent guarantees. They are proof that the system can be measured and improved.

## Stress Test Philosophy

Good tests should try to break the system honestly.

Useful stressors:

- stale context
- missing context
- contradictory files
- tired operator behavior
- ambiguous task packets
- partial completion
- tool replacement
- long gaps between sessions

The goal is not to prove the docs are perfect. The goal is to find where they fail before failure becomes operational drift.

## Evidence Standard

Every improvement should leave evidence:

- before state
- change made
- after state
- result
- remaining risk

If evidence is missing, the result is not proven.

