# Business Context

## Business Problem

The housing authority has more potential retrofit opportunities than available budget. Existing investment discussions rely heavily on energy-efficiency labels or broad property categories, but these do not provide a complete picture of where energy consumption is highest or which property segments may warrant further intervention assessment.

If prioritisation is based on a single rating or opaque scoring model, the authority risks directing investment inefficiently or introducing unintended bias through proxy variables such as geography or property characteristics.

The business problem is to create an explainable portfolio-level evidence base that combines consumption, property characteristics and efficiency-measure history while keeping the final investment decision under human control.

## Required Delivery Response

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

## How the Client Will Use the Output

The finished product should support an investment-planning workshop. A Housing Investment Director should be able to compare scenarios such as prioritising the highest-consumption property segments versus balancing consumption with known efficiency measures, see how the priority list changes, and understand which variables are driving the result.

The tool should support feasibility review and portfolio planning. It must not automatically allocate funding or claim that a retrofit intervention will definitely reduce consumption.

## Client
**Confidential Regional Housing & Net Zero Investment Authority**

## Problem
The authority has a constrained retrofit budget and cannot fund every eligible property. Previous prioritisation relies too heavily on headline efficiency ratings, with limited use of actual consumption, property characteristics or intervention history.

## Decision Owner
**Director of Housing Investment**

## Stakeholders
Head of Asset Management, Net Zero Programme Lead, Finance Business Partner, Housing Strategy Lead, Data Governance Lead, Energy Analyst, BI & Insight Lead

## Decision
**Which property segments should receive retrofit investment first to maximise defensible energy-efficiency benefit while keeping the prioritisation transparent, explainable and fair?**

## Role Responsibilities
| Role | Required contribution |
|---|---|
| Business Analyst | Define investment decision, stakeholder needs, constraints, scenarios and acceptance criteria. |
| Data Governance Analyst | Govern property/consumption definitions, source lineage, quality, proxy use and decision rules. |
| Data Engineer | Build reproducible preparation and curated property-level model. |
| Housing/Energy Data Analyst | Own consumption, property-segment and intervention-history analysis. |
| BI Developer | Build portfolio, segment and scenario decision-support views. |
| Data Scientist | Develop transparent segmentation/prioritisation model where justified. |
| AI/Model Governance Analyst | Assess explainability, proxy bias, validation, sensitivity and human oversight. |

## Evidence Chain
**Requirement → governed definition → transformation → quality control → metric/analysis → decision insight → recommendation → UAT**
