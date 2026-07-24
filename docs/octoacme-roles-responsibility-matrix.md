# OctoAcme Roles Responsibility Matrix (RACI)

This reference maps role ownership across the OctoAcme lifecycle phases to clarify accountability and cross-functional support.

## RACI legend
- **R** = Responsible (does the work)
- **A** = Accountable (owns outcomes/sign-off)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

## Lifecycle responsibility matrix

| Role | Initiation | Planning | Execution | Release | Retrospective |
| --- | --- | --- | --- | --- | --- |
| Developers | C | R | R | R | C |
| Product Managers (including Product Lead) | A | A | C | C | A |
| Project Managers | R | A | A | C | R |
| Engineering Lead / Tech Lead | C | R | A | C | C |
| QA / Test Engineer | I | C | R | R | C |
| Designer / UX Researcher | C | R | C | I | C |
| Release Manager | I | C | C | A | C |
| Stakeholder / Sponsor | A | C | I | I | C |
| Support / Customer Success | I | C | C | R | R |

## Notes
- Escalation path alignment: Team -> PM -> Product Lead -> Sponsor.
- Release ownership aligns with the Release & Deployment guide: readiness checks, smoke tests, deployment coordination, rollback readiness, and stakeholder/support communication.
