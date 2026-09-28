# NovaPay Technologies - GRC Risk Dashboard

> *20 fintech risks. A structured 5×5 risk assessment translated into an executive reporting dashboard.*

![Dashboard Preview](The%20Full%20Dashboard%20Overview.jpeg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
[![Made with Power BI](https://img.shields.io/badge/Tool-Power%20BI-orange)]()
[![Framework: ISO 27001](https://img.shields.io/badge/Framework-ISO%2027001-blue)]()
[![Framework: PCI-DSS](https://img.shields.io/badge/Framework-PCI--DSS%20v4.0.1-red)]()
[![Framework: NDPR](https://img.shields.io/badge/Framework-NDPR-green)]()

---

## Author

**Taiwo Johnson** | GRC & Cybersecurity Risk Analyst

Tools: Power BI · DAX · ISO 27001:2022 · PCI DSS v4.0.1 · NDPR/NDP Act

## Executive Summary

NovaPay Technologies is a **fictional fintech scenario created for portfolio demonstration**. The project models an information-security risk register for a payment-processing environment and translates the register into an executive reporting dashboard.

The assessment contains **20 prioritised risks across 9 risk categories**:

- **1 Critical** risk
- **5 High** risks
- **13 Medium** risks
- **1 Low** risk
- **10 Open** risks
- **8 In Progress** risks
- **2 Closed** risks

The dashboard is designed to demonstrate risk identification, 5×5 scoring, ownership, treatment tracking, and management reporting. It is a portfolio simulation, not evidence of an actual NovaPay assessment or certification.

## Scope

| In Scope | Out of Scope |
|---|---|
| Information-security risks across a simulated payment-processing environment | Physical security of third-party data-centre facilities |
| Risk scoring using a 5×5 likelihood × impact model | Full ISO 27001:2022 Annex A control assessment |
| Control ownership and treatment status | Penetration-testing findings or technical vulnerability validation |
| Illustrative mapping to ISO 27001:2022, PCI DSS v4.0.1, and Nigerian data-protection obligations | Quantitative financial risk modelling |
| Governance, compliance, technology, people, operational, cloud, and third-party risk themes | A complete enterprise-wide third-party risk assessment |

## Assessment Assumptions

1. The risk register is a portfolio simulation rather than a live organisational register.
2. Likelihood and impact scores are qualitative judgements for demonstration purposes, not actuarial loss estimates.
3. Risk scores are calculated as **Likelihood × Impact**.
4. Rating thresholds are applied consistently to every risk using the matrix below.
5. Risk ownership and treatment status are illustrative and would require validation with accountable business owners in a production environment.
6. The scenario represents a point-in-time assessment and is not an exhaustive inventory of all possible risks.

## Risk Rating Criteria

All risks use a **5×5 likelihood and impact matrix**, producing scores from 1 to 25.

### Likelihood Scale

| Score | Rating | Definition |
|---|---|---|
| 1 | Rare | May occur only in exceptional circumstances |
| 2 | Unlikely | Could occur at some point |
| 3 | Possible | Might occur at some point |
| 4 | Likely | Will probably occur in most circumstances |
| 5 | Almost Certain | Expected to occur frequently |

### Impact Scale

| Score | Rating | Definition |
|---|---|---|
| 1 | Negligible | Minimal disruption or limited business effect |
| 2 | Minor | Limited disruption with manageable consequences |
| 3 | Moderate | Significant disruption or moderate business impact |
| 4 | Major | Serious disruption, regulatory or customer impact |
| 5 | Critical | Severe consequences including major data, regulatory, or business impact |

### Risk Rating Matrix

| Risk Score | Rating | Treatment Requirement |
|---|---|---|
| 20-25 | Critical | Immediate remediation and escalation |
| 12-19 | High | Treatment plan and accountable owner |
| 6-11 | Medium | Treatment plan and periodic monitoring |
| 1-5 | Low | Accept, monitor, or otherwise manage according to risk appetite |

### Current Risk Distribution

The current register produces the following distribution under the stated matrix:

| Rating | Count |
|---|---:|
| Critical | 1 |
| High | 5 |
| Medium | 13 |
| Low | 1 |
| **Total** | **20** |

This distribution replaces the earlier inconsistent classification in which several score-10 risks were labelled High and score-15 risks were labelled Critical despite the stated thresholds.

## Risk Register

The dashboard contains 20 risks with the following core fields:

- Risk ID
- Risk description
- Risk category
- Threat source
- Likelihood
- Impact
- Calculated score
- Rating
- Treatment status
- Control owner

The dashboard applies the same scoring logic across the register so the score and rating remain aligned with the documented methodology.

## Regulatory and Framework Context

The portfolio uses ISO 27001:2022, PCI DSS, and Nigerian data-protection concepts as illustrative reference points. It does **not** claim that the simulated risks constitute a formal compliance assessment.

PCI DSS references have been updated to **v4.0.1**, the current version identified in the PCI Security Standards Council document library. PCI DSS v4.0 was retired on 31 December 2024. 

For Nigerian data protection, the project now refers to the **Nigeria Data Protection Act 2023 and applicable NDPC guidance** rather than treating the earlier wording as a blanket rule for every breach scenario.

## Dashboard Visuals

| File | Description |
|---|---|
| `The Full Dashboard Overview.jpeg` | Full GRC risk monitoring view |
| `Critical filter active.jpeg` | Critical-risk view |
| `Open status filter active.jpeg` | Open-risk view |
| `Image Breakdown.jpeg` | Risk breakdown by category and severity |
| `Image map.jpeg` | Risk map across business domains |

## Implementation

### Power BI

The original analytical dashboard was developed in Power BI using a structured risk register and DAX-based reporting logic.

### HTML Presentation Layer

A lightweight HTML/Chart.js version is included so the project can be inspected interactively through GitHub Pages without requiring Power BI Desktop.

The HTML version is a **presentation layer for the portfolio project**, not a replacement for an enterprise GRC platform.

## How to Use

1. Open `NovaPay_Risk_Dashboard.pbix` in Power BI Desktop for the Power BI version.
2. Review the dashboard screenshots for the visual output.
3. Open the HTML dashboard for an interactive browser-based view.
4. Review the risk register and methodology in this README.

## Lessons Learned

**1. Risk scoring without agreed criteria creates inconsistency**

A risk register is only defensible when the scoring methodology is defined before individual risks are rated. The current implementation calculates scores from likelihood × impact and applies one threshold matrix consistently.

**2. Ownership without accountability is decoration**

Assigning an owner is not enough. In a production environment, the owner needs authority, treatment actions, target dates, and evidence of progress.

**3. Dashboard design affects decision quality**

The dashboard separates risk posture, treatment status, and the underlying register so management can move from summary indicators to individual risks.

**4. Framework mapping should support one risk view**

ISO 27001, PCI DSS, and data-protection obligations can overlap, but mapping should be explicit and evidence-based rather than assuming that one control automatically satisfies every framework requirement.

**5. Treatment status needs a clear definition**

Open, In Progress, and Closed should represent defined workflow states. A production register would also require evidence, target dates, validation, and acceptance criteria before a risk is considered resolved.

## Limitations

1. **Portfolio simulation** - The scenario and organisation are fictional.
2. **Qualitative scoring** - The model does not quantify financial loss.
3. **Limited risk inventory** - Twenty risks do not represent a complete enterprise risk universe.
4. **No independent control testing** - The project does not provide penetration-test, audit, or control-test evidence.
5. **Manual data model** - The portfolio data is not connected to a live GRC platform.
6. **Illustrative framework mapping** - The dashboard demonstrates GRC thinking but is not a formal certification or compliance opinion.
7. **Static evidence** - Production implementations would require versioned evidence, approvals, audit trails, and access controls.

## Production Evolution

| Portfolio Version | Production Version |
|---|---|
| Structured risk register | Integrated GRC platform |
| Manual data updates | Controlled workflow and automated refresh |
| Qualitative scoring | Qualitative plus quantitative analysis where appropriate |
| Single analyst | Risk owners, GRC, security, compliance, and assurance stakeholders |
| Static evidence | Versioned evidence with approval and audit trail |
| Public portfolio dashboard | Role-based access with controlled disclosure |
| Illustrative framework mapping | Validated control-to-requirement mapping |
| Periodic review | Risk-triggered and scheduled review process |

## Roadmap

- [ ] Automate risk scoring
- [ ] Add treatment due dates and overdue indicators
- [ ] Add control effectiveness and residual-risk fields
- [ ] Add explicit framework/control mappings
- [ ] Integrate quantitative risk analysis
- [ ] Add vendor-risk assessment module
- [ ] Add audit trail and evidence tracking

## License

MIT License - see [LICENSE](LICENSE) for details.
