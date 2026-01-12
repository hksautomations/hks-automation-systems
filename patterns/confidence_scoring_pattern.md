# Confidence Scoring Pattern

## Problem
Not all AI outputs are equally reliable, but most systems treat them the same.

## Pattern
Require AI to self-evaluate confidence and expose:
- Confidence score (numeric or categorical)
- Reasoning summary
- Known uncertainties

System behavior changes based on confidence:
- High → auto-execute
- Medium → review
- Low → block or escalate

## When to Use
- RAG systems
- Research generation
- Lead scoring
- Classification tasks

## Benefits
- Smarter automation
- Reduced false positives
- Explainable AI behavior

## Common Failures Prevented
- Overconfident AI decisions
- Low-quality output propagation
