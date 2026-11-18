# Data Governance

## Principles
- Data minimization
- Purpose limitation
- Least-privilege access
- Secure secret management
- Separation of individual support data and aggregated intelligence
- Human review before public-health action
- Auditability

## Intelligence dataset

Where possible, the intelligence layer should use:
- topic/category
- date/time bucket
- anonymized or aggregated counts
- channel/source
- geographic level only when safe and authorized

Avoid sending raw personal information to the intelligence layer.

## Example signal

Illustrative only:

| Week | Heat-related information requests |
|---|---:|
| Week 1 | 42 |
| Week 2 | 51 |
| Week 3 | 89 |
| Week 4 | 117 |

Possible system output:

> Increasing demand for heat-related health information observed over the last two weeks. Public-health review recommended.

This is an information-demand signal, not an outbreak diagnosis.
