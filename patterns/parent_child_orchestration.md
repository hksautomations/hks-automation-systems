# Parent–Child Workflow Orchestration Pattern

## Problem
Large AI automation workflows become fragile and unmaintainable when built
as a single linear flow.

Failures cascade, logic becomes tangled, and changes are risky.

## Pattern
Split the system into:
- A **parent workflow** (orchestrator)
- Multiple **child workflows** (specialized executors)

The parent controls:
- Scheduling
- Routing
- Decision gates
- Failure handling

Child workflows handle:
- One responsibility only
- AI reasoning or deterministic processing
- Clear inputs and outputs

## When to Use
- Multi-stage AI systems
- Lead processing pipelines
- Research or content generation flows
- Systems that must scale safely

## Benefits
- Isolated failures
- Easier debugging
- Reusable child modules
- Safe system evolution

## Common Failures Prevented
- Monolithic workflow collapse
- Accidental infinite loops
- Untraceable AI errors
