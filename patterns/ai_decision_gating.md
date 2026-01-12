# AI Decision Gating Pattern

## Problem
AI outputs are probabilistic and may be incorrect, incomplete, or hallucinated.
Blindly executing AI decisions can cause serious failures.

## Pattern
AI is used for **recommendation**, not final authority.

Every AI decision passes through:
- Explicit rule-based gates
- Threshold checks
- Allowed / blocked outcome lists

Example gates:
- Apply / Review / Skip
- Proceed / Escalate / Stop

## When to Use
- Lead qualification
- Outreach automation
- Content publishing
- Any irreversible action

## Benefits
- Predictable behavior
- Reduced risk
- Auditable decisions
- Client trust

## Common Failures Prevented
- AI-triggered spam
- Wrong customer actions
- Silent logic errors
