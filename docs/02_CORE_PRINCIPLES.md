# Core Principles

Alexandria is built around a few operating principles. These are not decorative. They exist because repeated use exposed specific failure modes.

## 1. The Vault Is the Source of Truth

Chat history, agent memory, and model context are temporary. The written vault wins when sources conflict.

## 2. Markdown First

The system must remain readable without a database, app, runtime, or plugin.

## 3. State Is Not History

Current state should describe now. Logs should record what happened. Mixing the two creates stale authority.

## 4. Recoverability Over Optimization

A slower system that can be recovered after six months is better than a clever system that only works when everything is fresh.

## 5. Human Fatigue Is the Operating Environment

The system is designed for tired, interrupted, inconsistent use. If a process only works when the operator is perfectly disciplined, it is too fragile.

## 6. Explicit Over Implicit

Important rules belong in files. Unwritten habits do not survive context loss.

## 7. One Canonical Location Per Fact

Important facts need one home. Other docs may link or summarize, but duplication creates contradiction.

## 8. Archive Before Delete

Deletion removes recovery paths. Archive first, then reduce the active surface.

## 9. No Hidden Systems

Nothing important should run, enforce, or decide invisibly. If a tool or process affects the system, it must be discoverable.

## 10. Add Only What Failure Demands

Do not add structure because it sounds useful. Add the smallest durable fix after real use exposes a real failure.

## 11. Retrieval Should Be Proportional

Agents should read enough context to act safely, but not so much that signal is buried in noise.

## 12. Problem Solving Must Preserve Its Own Thread

Hard tasks need visible checkpoints: what is being tested, what changed, what evidence exists, what remains uncertain, and where to resume.

## Practical Standard

Every improvement should answer:

| Question | Why it matters |
|---|---|
| What failure does this solve? | Prevents ornamental complexity |
| What is the smallest useful change? | Controls system growth |
| How will we verify it worked? | Prevents vibes from becoming proof |
| What could it break later? | Keeps maintenance honest |
| Can a tired person recover this? | Tests real durability |

