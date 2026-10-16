# Project Brief

## Engagement Details
| Field | Detail |
|---|---|
| Project ID | MTL-XF-015 |
| Project Title | Housing Energy Efficiency, Consumption & Retrofit Prioritisation Intelligence |
| Client | Confidential Regional Housing & Net Zero Investment Authority |
| Sector | Housing / Energy / Net Zero |
| Duration | 8 weeks |
| Recommended Team Size | 6–8 |
| Primary Sponsor | Director of Housing Investment |
| Senior Stakeholders | Head of Asset Management, Net Zero Programme Lead, Finance Business Partner, Housing Strategy Lead, Data Governance Lead, Energy Analyst, BI & Insight Lead |
| Primary Dataset | National Energy Efficiency Data-Framework (NEED) Anonymised Data 2026 — 50,000-row sample |

## 1. Client Situation
The authority has a constrained retrofit budget and cannot fund every eligible property. Previous prioritisation relies too heavily on headline efficiency ratings, with limited use of actual consumption, property characteristics or intervention history.

## 2. Business Decision
> **Which property segments should receive retrofit investment first to maximise defensible energy-efficiency benefit while keeping the prioritisation transparent, explainable and fair?**

## 3. Agreed Objectives
1. Build a governed property/consumption analytical model from the frozen NEED sample.
2. Define transparent property, consumption and efficiency-measure fields suitable for portfolio analysis.
3. Identify segments with high consumption and plausible improvement opportunity without claiming causal treatment effects.
4. Develop an explainable retrofit-prioritisation framework that can be challenged by investment and governance stakeholders.
5. Provide scenario-based decision support that distinguishes measured evidence from policy assumptions.

## 4. Key Business Questions
1. Which property characteristics are associated with the highest observed energy consumption?
2. Which segments combine high consumption with evidence of prior/available efficiency measures?
3. How much do prioritisation results change under alternative weighting assumptions?
4. Which geographic/property proxies could introduce unfairness or misleading targeting?
5. What information is missing for a real investment decision, such as cost, tenure or household vulnerability?
6. Which interventions or segments warrant further feasibility assessment rather than automatic funding?

## 5. Cross-Functional Roles
| Role | Minimum expected output |
|---|---|
| Business Analyst | Define investment decision, stakeholder needs, constraints, scenarios and acceptance criteria. |
| Data Governance Analyst | Govern property/consumption definitions, source lineage, quality, proxy use and decision rules. |
| Data Engineer | Build reproducible preparation and curated property-level model. |
| Housing/Energy Data Analyst | Own consumption, property-segment and intervention-history analysis. |
| BI Developer | Build portfolio, segment and scenario decision-support views. |
| Data Scientist | Develop transparent segmentation/prioritisation model where justified. |
| AI/Model Governance Analyst | Assess explainability, proxy bias, validation, sensitivity and human oversight. |

## 6. Minimum Delivery Standard
Traceable requirements; governed definitions/lineage; preserved raw data; reproducible transformation; data-quality/reconciliation evidence; domain-specific analysis; transparent decision logic; governed BI; UAT; handover; visible collaboration.

## 7. Constraints
- Observed consumption does not prove that a retrofit measure caused a change.
- The anonymised sample is not a live housing stock register and must not be presented as one.
- Proxy variables must be reviewed for fairness and unintended targeting effects.
- No score should allocate funding automatically.
- Cost-effectiveness cannot be claimed without credible intervention cost and benefit assumptions.

## 8. Agreed Success Criteria
- The curated table retains a documented one-row-per-property/sample-unit grain and all derived fields are reproducible.
- At least five major analytical measures reconcile to direct calculations from the frozen NEED sample.
- Any prioritisation score exposes every component and weight; no hidden composite logic is allowed.
- At least three alternative weighting/scenario configurations are compared.
- A proxy/fairness review documents variables excluded or restricted from prioritisation.
- No recommendation is framed as proven causal retrofit impact without supporting evidence.

## 9. Out of Scope
Core delivery excludes confidential personal data, paid production infrastructure, automated operational decisions and unsupported causal inference.

## 10. Reproducibility Definition
A reviewer should be able to clone the team repository, obtain the approved source data, run the documented workflow and reproduce curated outputs and validation evidence without undocumented manual changes.
