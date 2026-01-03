DAY 2 – Failure Mode Enforcement

Objective:
To define and enforce hard refusal rules for invalid or unsafe queries.

Failure Modes Enforced:
- Missing source
- Conflicting entries
- Age-group mismatch
- Low confidence on factual topics

Behavior:
All refusals are neutral, deterministic, and non-apologetic.

Contents:
- failure_rules.md: Defined refusal rules
- test_queries.md: 5 test queries triggering refusal
- refusal_outputs.md: Refusal responses
- logs/refusal.log: Log evidence of refusal decisions

No scope creep was introduced.

