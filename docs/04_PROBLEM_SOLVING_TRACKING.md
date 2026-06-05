# Problem Solving Tracking

Difficult work often fails because the reasoning thread gets lost.

Alexandria uses a lightweight problem card when a task has multiple moving parts, live debugging, competing interpretations, or a risk of interruption.

## Purpose

The card preserves:

- what is broken
- why it matters
- what hypothesis is being tested
- what evidence exists
- what changed
- what remains uncertain
- where to resume

It is not a second task system. It is a temporary scaffold for keeping the problem visible while it is being solved.

## Minimum Card

```md
## Problem Card - [short name]

Problem:
- [What is broken, confusing, or unresolved?]

Why it matters:
- [What understanding, continuity, safety, or workflow breaks if ignored?]

Current hypothesis:
- [What do we think is causing it? Mark as hypothesis, not fact.]

Checklist:
- [ ] Inspect current state
- [ ] Identify evidence
- [ ] Make smallest useful change
- [ ] Verify result
- [ ] Log outcome

Evidence:
- Before: [metric, file state, observed behavior]
- After: [metric, file state, observed behavior]
- Source files: [paths]

Stop condition:
- [What would make the agent stop and hand off instead of pushing forward?]

If interrupted, resume from:
- [Exact next step]
```

## When To Use It

Use a problem card when:

- a task has more than three meaningful steps
- debugging or repair is involved
- multiple files or systems interact
- before/after evidence matters
- a session might stop mid-task
- the operator asks to break something down

Do not use it for simple edits or routine answers.

## Why It Matters

The card makes the difference between:

- "we were trying things"
- "we tested this hypothesis, changed this file, saw this result, and should resume here"

That difference is continuity.

## Operating Rule

Track the problem, not every motion. Completed work belongs in logs and reports. The card exists only to make live reasoning recoverable.

