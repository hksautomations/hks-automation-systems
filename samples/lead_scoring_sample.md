# Sample: AI Lead Scoring

## Context
A new opportunity is collected from a job board or inbound form.

The system must decide whether to:
- Apply
- Review
- Skip

## Input (Sanitized)
- Job description: "Looking for an AI automation expert to build a lead qualification system"
- Budget: Mentioned
- Timeline: 2–4 weeks

## AI Evaluation (Simplified)
- Portfolio relevance: High
- Clarity of requirements: Medium
- Budget signals: Positive
- Risk indicators: Low

## Confidence Score
0.82 (High)

## Decision Gate
IF confidence ≥ 0.75 → Allow auto-processing

## Outcome
✔ Classified as **Apply**
✔ Routed to pitch generation workflow

## Patterns Used
- AI Decision Gating
- Confidence Scoring
- Parent–Child Orchestration
