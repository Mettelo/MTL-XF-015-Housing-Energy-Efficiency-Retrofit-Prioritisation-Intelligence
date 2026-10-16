# Project Brief

## 1. Business Problem

The housing authority has more potential retrofit opportunities than available budget. Existing investment discussions rely heavily on energy-efficiency labels or broad property categories, but these do not provide a complete picture of where energy consumption is highest or which property segments may warrant further intervention assessment.

If prioritisation is based on a single rating or opaque scoring model, the authority risks directing investment inefficiently or introducing unintended bias through proxy variables such as geography or property characteristics.

The business problem is to create an explainable portfolio-level evidence base that combines consumption, property characteristics and efficiency-measure history while keeping the final investment decision under human control.

## What the Team Needs to Do

The team is expected to build a responsible retrofit-prioritisation decision-support product.

The work should include:
- defining investment constraints, users and decision criteria;
- building a governed property-level analytical dataset;
- documenting consumption, property and efficiency-measure fields;
- analysing energy consumption by property segment;
- identifying high-consumption and potentially improvable segments;
- designing an explainable prioritisation framework;
- comparing at least three alternative weighting/scenario configurations;
- performing a proxy/fairness review;
- identifying data that is missing for a true investment case, such as intervention cost, tenure or household vulnerability;
- building scenario-based BI that clearly separates observed data from assumptions;
- completing model-governance review, UAT and handover.

## Practical Use Case

The finished product should support an investment-planning workshop. A Housing Investment Director should be able to compare scenarios such as prioritising the highest-consumption property segments versus balancing consumption with known efficiency measures, see how the priority list changes, and understand which variables are driving the result.

The tool should support feasibility review and portfolio planning. It must not automatically allocate funding or claim that a retrofit intervention will definitely reduce consumption.

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
