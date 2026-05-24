# Prioritization Model

## Purpose
Provide a consistent, explainable model for triaging fictional enterprise mainframe customer requests while preserving PM judgment.

## Criteria Used
- Renewal / retention risk
- Regulatory or audit impact
- Customer severity
- Revenue impact
- Engineering effort
- Modernization value
- Support burden reduction
- Adoption potential
- Strategic fit
- Number of customers affected

## Lightweight scoring approach
1. Score each criterion from 1 (low) to 5 (high).
2. Apply weights (see triage matrix).
3. Invert engineering effort in the blended score so very high effort does not automatically dominate high-risk items.
4. Generate a suggested priority band (P0–P3).
5. Apply PM override only with written rationale in request notes.

## PM decision guardrails
- High regulatory impact plus high renewal risk should usually remain in P0/P1 unless a clear mitigating control exists.
- Modernization opportunities should be prioritized when they reduce disruption risk for existing workflows.
- Repeated support pain should be considered for roadmap investment if it meaningfully reduces operational friction.

## Output used in dashboard
- Overview cards show aggregate risk and priority load.
- Filters support fast discussion by risk theme.
- Detail panel captures PM recommendation and reasoning.
